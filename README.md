# LibParserSaver

## Общее описание
Библиотака, позволяющая легко обрабатывать и сохранять в другой форме xml-документы.

- Parser предоставляет возможность при помощи одной функции преобразовать xml-документ в strust.
- Saver - сохранить strust в любой требуемой под конкретный проект форме.

Более подробное описание в папке doc

## Как собирать и устанавливать
Для работы необходимо установать pugixml

```
sudo apt update
sudo apt install libpugixml-dev
```
либо
```
git clone https://github.com/zeux/pugixml.git
cd pugixml
mkdir build
cd build
cmake ..
make
sudo make install
```

Сборка и установка LibParserSaver
```
cd build
cmake ..
make
sudo cmake --install .
```
