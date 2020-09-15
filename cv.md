[My CV](https://karinamasalova.github.io/rsschool-cv/cv)
# Karina Masalova
## Contact Info
* Email: masalova.karina@mail.ru
* Telephone number: [+375447362189](+375447362189)
* Telegram: [@karinamasalova](https://t.me/karinamasalova)
* LinkedIn: [https://www.linkedin.com/in/karina-m-786a19134](https://www.linkedin.com/in/karina-m-786a19134)
* Vk: [https://vk.com/karina_masalova18](https://vk.com/karina_masalova18)

## Summary
My goal is to be in a space, where people create useful things and make high demands on themselves. I'm an ambitious and self-motivated person, trying to dig deeply and do my best. It's easy for me to get along with people. My favourite quote sounds like:
> Your future is created by what you do today, not tomorrow.

## Skills

* HTML5
* CSS3   
* Flexbox
* PerfectPixel
* Cross-browser compatibility
* Adaptive / Responsive
* Bootstrap  
* JavaScript 
* Git / Github   
* Webpack 
* ESLint  
* React

## Code examples
**JavaScript**
```
function findDup(arr) {
    let duplicateValue;
    
    arr.sort(function sortArray(a, b) {
        return a - b;
    });
    
    for (let i = 0; i < arr.length - 1; i++) {
        for (let j = i + 1; j < arr.length; j++) {
            if(arr[i] == arr[j]) {
            duplicateValue = arr[i];
            }
        }
    }
    return duplicateValue;
}
```
**HTML**
```
<div class="icon-area">
    <div class="wrap">
        <div class="better-design">
            <div class="img-design"></div>
            <p class="text-design">better design</p>
        </div>
        <div class="customise">
            <div class="img-cust">
                <img src="./assets/img/customise.svg" alt="">
            </div>
            <p class="text-cust">customise</p>
        </div>
        <div class="its-free">
            <div class="img-free"></div>
            <p class="text-free">its free</p>
        </div>
    </div>
</div>
```
**CSS**
```
.wrap {
        margin: 0 auto;
        width: 100%;
        max-width: 1020px;
    }
    
.better-design,
.customise,
.its-free {
    height: 211px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
```
**JavaScript**
```
const app = new App();
let page = 1;
let currentQuery = 'dream';
let isNextQuery;
const loader = (query, currentPage) => {
  isNextQuery = false;
  loadMovieData(query, currentPage)
    .then((data) => {
      if (data.Response === 'True') {
        const movies = data.Search.map((obj) => new Movie(obj));
        const slides = movies.map((movie) => new SwiperSlide(movie));
        app.swiper.appendSlide(slides.map((s) => s.element));
      }
    });
};
```

**C++**
```
Manager* Manager::printStudentInfo() {
    for (int i = 0; i < currentStudentSize; i++) {
        student[i].printStudentInfo();
    }
    return nullptr;
}

Criteria* Manager::findCriteriaById(int studentID, int specialistID) {
    for (int i = 0; i < currentCriteriaSize; i++) {
        if ((criteria[i].get_spID() == spID) && (criteria[i].get_stID() == stID)) {
            return &criteria[i];
        }
    }
    return nullptr;
}

Student* Manager::deleteStudentBySurname(string stSurname) {
    for (int i = 0; i < currentStudentSize; i++) {
        if (student[i].get_stSurname() == stSurname) {
            for (int j = i; j < currentStudentSize - 1; j++) {
                student[j] = student[j + 1];
            }
        currentStudentSize--;
        }
    }
    return nullptr;
}
```

## Experience
* Educational practice in web studio (2 weeks in summer, 2019)
* Tasks on Codewars: https://www.codewars.com/users/KarinaMasalova
* Online courses on Codeacademy: https://www.codecademy.com/users/karinamasalova/achievements
* Coursework on C++ (console application), 2018
* Translation of technical documentation on Contribution Day on Drupal Camp Belarus 2019

## Education
* The Academy of Public Administration under the aegis of the President of the Republic of Belarus (incomplete higher education)
* RSS (Frontend Development)

## English
My English level is B1.
