DeletePlusZero (���� PlusNonZero)
����������� �� ������ ���� 0+expr
������� ������� opt, �������� ���:
PlusNonZero opt = new PlusNonZero();
r.Visit(opt);
������� ��� ���������� ����� ������ ����� ����� PrettyPrintVisitor:
PrettyPrintVisitor ppvis = new PrettyPrintVisitor();
r.Visit(ppvis);
Console.WriteLine(ppvis.Text);