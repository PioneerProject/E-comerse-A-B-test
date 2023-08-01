# ������ A/B ������������

## �������� ���� ������������:
��������� ���������� ������������ �/� ������������ � ���������� ������������ �� ��������� ������� �� 10%

## ����������� �������:

- ����������� ����: recommender_system_test;
- ������ ������������: � � �����������, B � ����� �������� �������;
- ���� �������: 2020-12-07;
- ���� ��������� ������ ����� �������������: 2020-12-21;
- ���� ���������: 2021-01-04;
- ���������: � ���� ������ ���� �������� 15% ����� ������������� �� ������� EU;
- ���������� �����: ������������ ���������, ��������� � ���������� ���������� ���������������� �������;
- ��������� ���������� ���������� �����: 6000.
- ��������� ������: �� 14 ���� � ������� ����������� ������������ ������� ��������� ������ ������� �� �����, ��� �� 10%:
- ��������� � �������� �������� ������� � ������� product_page,
- ��������� ������� � product_cart,
- ������� � purchase.

## ������:
- final_ab_events.csv
- ab_project_marketing_events.csv
- final_ab_new_users.csv
- final_ab_participants.csv

## �������� ������:

- ab_project_marketing_events.csv � ��������� ������������� ������� �� 2020 ���.\
	��������� �����:\
		name � �������� �������������� �������;\
		regions � �������, � ������� ����� ����������� ��������� ��������;\
		start_dt � ���� ������ ��������;\
		finish_dt � ���� ���������� ��������.

- final_ab_new_users.csv � ������������, �������������������� � 7 �� 21 ������� 2020 ����.\
	��������� �����:\
		user_id � ������������� ������������;\
		first_date � ���� �����������;\
		region � ������ ������������;\
		device � ����������, � �������� ����������� �����������.

- final_ab_events.csv � �������� ����� ������������� � ������ � 7 ������� 2020 �� 4 ������ 2021 ����.\
	��������� �����:\
		user_id � ������������� ������������;\
		event_dt � ���� � ����� �������;\
		event_name � ��� �������;\
		details � �������������� ������ � �������. ��������, ��� �������, purchase, � ���� ���� �������� ��������� ������� � ��������.\

- final_ab_participants.csv � ������� ���������� ������.\
	��������� �����:\
		user_id � ������������� ������������;\
		ab_test � �������� �����;\
		group � ������ ������������.

## ���� ������������:

1. ���������������� ����.\
    1.1 ������ ����������� ���������\
    1.2 �������� ������ � ����������\
    1.3 ������������ � �������\
    1.4 ������ �� �������

2. ������������� ������\
    2.1 ���������� ������ � ��������������� �����\
    2.2 ������������ ��������� � ����������\
    2.3 ������ �� �������

3. ������ ������������ ���������� �����\
    3.1 �������� ������������ ������ ����������� ������������ �������. ��������� ������������ ���� ������� ��\
    3.2 �������� ������������ ������� ���������� ����� ������������� �  ������ �����������\
    3.3 �������� ����������� � �������������� ������� � ����������� ��������� � ������ ���� � ������.\
    3.4 �������� �� ������������� ������������� �� �������� ������� � ������������ �� ������������\
    3.5 ������ �� �������

4. ����������������� ������ ������\
    4.1 ���������� ������� �� ������������ ��������� ������������ � ��������?\
    4.2 ��� ����� ������� � �������� ������������ �� ����?\
    4.3 ��� �������� ��������� � ������� � �������� �� ������ ������?\
    4.4 ����� ����������� ������ ����� ������, ������ ��� ���������� � A/B-������������?\
    4.5 ������ �� �������

5. ������ ����������� �/�-������������\
    5.1 ��� ����� ������� ��� ���������� A/�-������������?\
    5.2 ��������� �������������� ������� ����� z-���������.\
    5.3 ������ �� �������

6.  ����� ������ �� ����� ������������������ ������� ������ � �� ���������� ������ ����������� A/B-������������. ���������� � ������������ ���������� �����.