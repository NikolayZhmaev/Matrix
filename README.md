# Matrix

en

An integer matrix is given in which there are N rows, and the number of elements in a row for each row can be any, including zero. Let's call the strings similar if the sets of numbers found in these strings coincide. Find a list of rows of this matrix of maximum dimension in which all rows are pairwise dissimilar to each other. From similar rows, include the row with the largest number in the list. The order of the items in the list is arbitrary.

Example. The matrix contains 3 rows:

> 1 2 2 4 4<br/>
> 4 2 1 4<br/>
> 3 2 4 1 5 8

The first 2 lines are similar to each other and unlike the 3rd line. The answer will be a list of 2 and 3 lines.

Create a MatrixNonSimilarRows class, which should have the following constructor and method:
1.	public MatrixNonSimilarRows(int[][] matrix)<br/>
    Creates MatrixNonSimilarRows based on the specified matrix.
2.	public List<int[]> getNonSimilarRows()<br/>
	  Returns a list of dissimilar strings.
    
***
ru

Дана целочисленная матрица, в которой имеется N строк, а число элементов в строке для каждой строки может быть любым, в том числе нулевым. Строки назовем похожими, если совпадают множества чисел, встречающихся в этих строках. Найти список строк этой матрицы максимальной размерности, в котором все строки попарно непохожи друг на друга. Из похожих строк в список включить строку с наибольшим номером. Порядок элементов в списке произвольный.

Пример. Матрица содержит 3 строки:

> 1 2 2 4 4<br/>
> 4 2 1 4<br/>
> 3 2 4 1 5 8

Первые 2 строки похожи друг на друга и непохожи на 3 строку. Ответом будет список из 2 и 3 строк.

Создайте класс MatrixNonSimilarRows, в котором должны быть следующие конструктор и метод

1.	public MatrixNonSimilarRows(int[][] matrix)<br/>
    Создает MatrixNonSimilarRows по заданной матрице.
2.	public List<int[]> getNonSimilarRows()<br/>
	  Возвращает список непохожих строк.
