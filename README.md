# Покупательская корзина.
## В нём должны быть методы:
### - конструктор, принимающий массив цен и названий продуктов;
### - addToCart(int productNum, int amount) - метод добавления amount штук продукта номер productNum в корзину;
### - printCart() - метод вывода на экран покупательской корзины.
### - saveTxt(File textFile) - метод сохранения корзины в текстовый файл; использовать встроенные сериализаторы нельзя;
### - static Basket loadFromTxtFile(File textFile) - статический(!) метод восстановления объекта корзины из текстового файла, в который ранее была она сохранена;
### - геттеры, которые вы посчитаете нужными.
### После ввода каждой покупки пользователем вам следует сохранять пользовательскую корзину в файл basket.txt. При старте программа должна искать этот файл в корне проекта и если он находится, восстанавливать корзину из него; если файл не найдет, то стоит начать с пустой корзины.