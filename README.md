[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-f4981d0f882b2a3f0472912d15f9806d57e124e0fc890972558857b51b24a6f9.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=9809738)
# Виконання ПР на 5 балів 


## Завдання 1. Створення та запуск першої програми (сорочки)

1. **клонуйте** створений для вас репозиторій в Netbeans
2. створіть в теці **src** новий файл **Shirt.java**, в якому наберіть наступний текст:

``` java
public class Shirt {
  public int shirtID = 0; // стандартне значення номера моделі сорочки
  public String description = "-description required-"; // стандартний опис сорочки
  // коди кольорів: R=червоний, B=синій, G=зелений, U=невідомо
  public char colorCode = 'U';
  public double price = 0.0; // стандартна вартість сорочки
  public int quantityInStock = 0; // стандартна кількість на складі
  
  // цей метод просто виводить всю інформацію про сорочку на екран
  public void displayShirtInformation() {
    System.out.println("Shirt ID: " + shirtID);
    System.out.println("Shirt description:" + description);
    System.out.println("Color Code: " + colorCode);
    System.out.println("Shirt price: $" + price);
    System.out.println("Quantity in stock: " + quantityInStock);
  } // кінець методу displayShirtInformation
} // кінець опису класу
```

3. **збережіть** файл
4. відкрийте файл **ShirtTest.java** з цього репозиторію
5. **запустіть** його
6. зробіть та збережіть (тека **Solution**) у файл task1.1.png **скріншот** результатів роботи програми 
![task1 1](https://user-images.githubusercontent.com/112692170/214913860-d70934e0-6556-4550-9335-456d3f47f690.png)


7. замініть у файлі **Shirt.java** номер сорочки, її опис та вартість довільними значеннями 
8. запустіть файл повторно
9. зробіть та збережіть у файл task1.2.png **скріншот** нових результатів роботи програми 
![task1 2](https://user-images.githubusercontent.com/112692170/214913861-9dff6fad-e682-472f-82ed-5e642410db48.png)


10. Змініть код, щоб колір сорочки зберігався та виводився у вигляді рядка (red, blue, green, unset) 
![task1 3](https://user-images.githubusercontent.com/112692170/214913858-84c5c040-15c9-4b71-9053-8c32facb477f.png)


## Завдання 2. Створення та запуск іншої програми (цитати)

1. додайте в проект (до теки **src**) файл **Quotation.java** з таким вмістом:

``` java
public class Quotation {
  String quote = "Welcome to Sun!";
  public void display() {
    System.out.println(quote);
  }
}
```
2. **збережіть** файл
3. відкрийте файл **QuotationTest.java** з цього репозиторію
4. **запустіть** його
5. зробіть та збережіть (тека **Solution**) у файл task2.1.png **скріншот** результатів роботи програми 
![task2 1](https://user-images.githubusercontent.com/112692170/214913970-9b3032c5-603c-4f77-814a-bc15b0c4f235.png)


6. замініть у файлі **Quotation.java** текст довільною цитатою, знайденою в Мережі
7. запустіть файл повторно
8. зробіть та збережіть (тека **Solution**) у файл task2.2.png **скріншот** нових результатів роботи програми 
![task2 2](https://user-images.githubusercontent.com/112692170/214913964-69dd34ce-89ec-4b7e-92ca-becdaab4c304.png)


9. Змініть код, щоб окрім цитати виводилось ім'я того, кому вона належить 
![task2 3](https://user-images.githubusercontent.com/112692170/214913968-e92c27f8-1b7b-47f5-987e-4b2048ec9f6c.png)
