# 1-  test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
##   `CREATE TABLE employee(id INTEGER PRIMARY KEY, name VARCHAR(50), birthday DATE, email VARCHAR(100));`

# 2-  Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
##   `insert into employee (id, name, birthday, email) values (1, 'Hedwig', '1900-11-02', 'hpaslow0@de.vu'); * 50`

# 3- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
##   `UPDATE employee SET name = 'Emre' WHERE id < 6;`

# 4- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
##   `DELETE FROM employee WHERE id > 44;`

