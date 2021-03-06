# ي : لغة البرمجة 

**_[YaLang (ي)](https://github.com/yalang/yalang)_** is an open source programming language where you can write python code in arabic language.

It takes the arabic text and convert it into python code and execute it. 
Which then can be used anywhere. You can code anything which you can code in python.


- **Hello World** [Sample File اهلا.ي](https://github.com/yalang/yalang-sample/blob/master/اهلا.ي)
```python
اكتب("اهلا و سهلا يا عالم")؛
```
Output:
```bash
اهلا و سهلا يا عالم
```

- **Condition** [Sample File لو.ي](https://github.com/yalang/yalang-sample/blob/master/لو.ي)
```python
ع = ٧
لو ع ٪ ٢ == ٠:؛
    اكتب("ع الفردية")؛
ولو ٧ == ٠:؛
    اكتب("هذا صفر")؛
آخر:؛
    اكتب("ع الزوجية")؛
```
Output:
```bash
ع الزوجية
```

- **Function** [Sample File وظيفة.ي](https://github.com/yalang/yalang-sample/blob/master/وظيفة.ي)
```python
وظيفة جمع(اولا، ثاني):؛
    كل = اولا + ثاني؛
    إرجع كل؛

اكتب("جمع = "، جمع(٢، ٣))؛
```
Output:
```bash
جمع =  ٥
```

**NOTE: `؛` is optional at the end of line**



For more sample code see (https://github.com/yalang/yalang-sample)


## Prerequisites
- macOS
- Python 3


## Getting Started
### Installation
- Clone this repo:
```bash
git clone https://github.com/yalang/yalang.git
cd yalang
```
- Run install.sh:
```bash
./install.sh
```
- Add `export PATH=$HOME/yalang/bin:$PATH` to `.bash_profile` or `.bashrc`


## Running

- Create a new file with name `اهلا.ي` and open in any editor.

- Write this in the file

```vim
اكتب("اهلا و سهلا يا عالم")؛
```

- Save it

- Open a terminal and go to the folder where file is saved

- Run this command

```bash
ي اهلا
```

- It will print 

```bash
اهلا و سهلا يا عالم
```
