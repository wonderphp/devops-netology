в Файле terraform/.gitignore будут проигнорированны следующией файлы(далее абсолютный путь в условиях поиска начинается от файла .gitignore)

0. **/.terraform/* в любом месте скрытый каталог .terraform (из просторов интернета: **- Два соседних символа звездочки соответствуют любому файлу или нуля или более каталогов. Когда за ним следует косая черта ( /), он соответствует только каталогам.)
1. С расширением *.tfstate и содержащие .tfstate. в строке имени
2. crash.log
3. С расширением .tfvars, которые содержат какие то пароли 
4. override.tf, override.tf.json. Оканчивающиеся на *_override.tf и на *_override.tf.json
5. Исключение ! заакоменчено
6. С расширением .terraformrc и terraform.rc
