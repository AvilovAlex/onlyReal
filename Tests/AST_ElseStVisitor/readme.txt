ElseStVisitor
12 �������� �������� if �� ��� ����� else � ������, ���� ������� �����. if (false) st1; else st2; st2
����� �������� ��� ����������� ����� ��������� AST, � ��������� ��������� ���:
var r = parser.root;    // ������ AST
r.Visit(new FillParentVisitor());   // ��������� ������ �� ��������� �� AST
r.Visit(new ElseStVisitor());	// ���������� ������� �����������
