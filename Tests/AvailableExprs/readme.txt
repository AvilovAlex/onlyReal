AvailableExprs
��������� ���������-��������� e_genB, e-KILLb. ������������ ������� ��� �.
���� AvailableExprs.cs
var ae = new AvaliableExprs(); // ����� ����� ��������� ���������
var rr = ae.GetGenAndKillerSets(blocks); // ���������� ��� ��������, ������ ��� e_gen, ������ e_kill. ��� ������� rr.Item1 (Item2) ����� ��� ���� ������
var ttt = ae.TransferByGenAndKiller(rr.Item1[i], rr.Item1[i], rr.Item2[i]); // ���������� ��� ������� �����, i-����� �����. ���������� HashSet<(string, string, string)>