# **Pavel Evtushenko**
-
## **Contacts**
-
* Telegram: [t.me/stclamp](@stclamp)
* Email: [whatisclamp@gmail.com]
* Phone: +380952453087

## **About**
-
Hi! I'm Pavel. I'm from Ukraine, Donetsk region. Now I study at RS School. 
My dream is to become a professional in front-end development. I am good at creating websites. I know basic JavaScript. And every day I improve my knowledge

## **Skills**
-
* HTML
* CSS
* Native JS
* React
* Git

## **My Code Example**
-
```

const humburgerImg = document.querySelector('.humburger__img');
const headerList = document.querySelector('.header__list');
const headerItems = document.querySelectorAll('.header__item');
const close = document.querySelector('.humburger__close');


humburgerImg.addEventListener('click', () => {
    headerList.classList.add('active');
    headerItems.forEach(item => {
        item.classList.add('active');
    });
    dropDownBtn.classList.add('active');
    close.style.display = 'block';
    humburgerImg.style.display = 'none';
});

close.addEventListener('click', () => {
    headerList.classList.remove('active');
    headerItems.forEach(item => {
        item.classList.remove('active');
    });
    dropDownBtn.classList.remove('active');
    close.style.display = 'none';
    humburgerImg.style.display = 'block';
});

```

## **English**
-
Now I Have A1 English level
