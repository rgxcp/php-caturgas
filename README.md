# PHP - Caturgas (Catat dan Atur Tugas)
EN : Website-based task note-taking application uisng PHP with CRUD functions.
ID : Aplikasi pencatat tugas berbasis website menggunakan PHP dengan fungsi CRUD.

## Requirements
1. XAMPP
2. Database
3. Table

## How to Use
1. Clone this repository to `htdocs` folder in `XAMPP` installation folder. Ex: `$:\XAMPP\htdocs`.
2. Fire-up XAMPP and start Apache & MySQL Module.
3. Visit [PHPMyAdmin](http:/127.0.0.1/phpmyadmin).
4. Create the database.
   ```
   CREATE DATABASE `sbd_satu`;
   ```
5. Create the table. 
   ```
   CREATE TABLE `sbd_satu`.`caturgas` ( `id` INT NOT NULL AUTO_INCREMENT , `matkul` VARCHAR(50) NOT NULL , `tugas` VARCHAR(200) NOT NULL , `deadline` VARCHAR(50) NULL , PRIMARY KEY (`id`)) ENGINE = InnoDB; 
   ```
6. Visit [Index Page](http:/127.0.0.1/php-caturgas/index.php).
7. Do-what-you-want-with-it!.