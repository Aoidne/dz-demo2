using System;

// class Program
// {
//     static void Main()
//     {
string title;
string author;
int publicationEyar;
string isbn;

Console.Write("Введите название книги");
title = Console.ReadLine();

Console.Write("Введите автора");
author = Console.ReadLine();

Console.Write("Введите год издания");
publicationEyar = int.Parse(Console.ReadLine());

Console.Write("Введите ISBN");
isbn = Console.ReadLine();

Console.WriteLine("\n--- Введённые данные о книге ---");
        Console.WriteLine($"Название: {title}");
        Console.WriteLine($"Автор: {author}");
        Console.WriteLine($"Год издания: {publicationEyar}");
        Console.WriteLine($"ISBN: {isbn}");
