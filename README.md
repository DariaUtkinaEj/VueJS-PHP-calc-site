# VueJS-PHP-calc 
## Hi, there! This is my new Javascript pet-project!
Деплой на моем сайте: https://just-for-fun-myapps.ru/ - можно потыкать приложение здесь!

* This site is an online loan and mortgage calculator, 
the template and appearance are 
made according to the real mortgage calculator, 
which I took as an example from the Sberbank website. This is my 
version of the calculator.
* [Sbarbank site](https://www.sberbank.ru/ru/person/credits/home/buying_complete_house) is here.
There you can see original online sber-calc.
* ## My project is logically built according to the mvc pattern. 
However, I want to mention some features, that distinguish my logic from the most familiar MVC behavior. In my case there are:
* Model -- Which is responsible only for the data.
* View -- This is not only the appearance or the presentation, I also implemented listening to various events, input, initialization here. So VIEW is not responsible ONLY for displaying the UI on the screen.
* Controller -- Which responsible for linking data to the display and is responsible for synchronizing the model and view.


## I used the following tools in my project:
1. [Vue.js Framework](https://ru.vuejs.org/) - vue.js framework for the frontend part of application.
2. Lib [NoUISlider](https://refreshless.com/nouislider/) - slider to define the value interval; noUiSlider is a lightweight range slider with multi-touch support and a ton of features.
3. Lib [wNumb](https://refreshless.com/wnumb/) - wNumb is a formatting library with a dead-simple interface. It has two methods: to and from.
4. Lib [Cleave.js](https://nosir.github.io/cleave.js/) - Cleave.js has a simple purpose: to help you format input text content automatically.
5. Lib [Parcel.js](https://parceljs.org/) - It is a very fast multifunctional module builder that supports HTML, CSS, JavaScript, Image and TypeScript resources without the need for separate plugins. The main thing is that Parcel does not require configuration, it is enough just to send it to the initial file – and Parcel will independently combine, transform and minimize all resources.
6. Also, I used Live-Server (Visual Studio Code Extension) for JS and Open server while writing php-code.

## The way you can get my project to your local machine and open it:
* STEP ONE: git clone https://github.com/DariaUtkinaEj/VueJS-PHP-calc-site
* STEP TWO: Please, put it in your local web server folder (for example, OpenServer -> domains, and then open my site with your browser)
* Or else, open it with help of Visual Studio Code (install VSCode & Live Server Extension for VSCode) and then do this: open file 'index.html' with LiveServer. Check localhost with your browser. Enjoy! 