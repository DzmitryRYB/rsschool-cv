## [rsschool-cv](https://DzmitryRyb.github.io/rsschool-cv/cv)


# Dzmitry Rybakou


## Contacts
* **Phone:** +375 29 6537372
* **Email:** rubakovdima81@gmail.com
* **GitHab:** DzmitryRyb
* **Discord:** Rybakov Dima (@dzmitryryb)


## About me
I am new to the IT field, but I like to learn and I am sure that I will succeed.


## Skills
* Python
* HTML&CSS
* Git
* Adobe illustrator
* Adobe Photoshop
* Autodesk Maya


## Code exemple
```
def debug(func):
    def inner(*args, **kwargs):
        print('параметры -> ', *args)
        print('возвр. значение -> ', func(*args))
        return func(*args, **kwargs)
    return inner

@debug
def summ_of(a, b):
    resl=a+b
    return resl

@debug
def multip_of(a, b, c):
    resl=a*b*c
    return resl

print('resl func =', summ_of(10, 20))
print('resl func =', multip_of(2, 5, 4))
```