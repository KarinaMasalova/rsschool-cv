[My CV](https://karinamasalova.github.io/rsschool-cv/cv)
# Karina Masalova
## Contact Info
* Email: masalova.karina@mail.ru
* Telephone number: [+375447362189](+375447362189)
* Telegram: [@karinamasalova](@karinamasalova)
* Vk: [https://vk.com/karina_masalova18](https://vk.com/karina_masalova18)

## Summary
I'm a student and interested in web development. My strengths are: responsibility, discipline and I'm a quick-learning person, if something causes my interest. I also know how to work in a team, it's easy for me to get along with people. My favourite quote sounds like:
> Your future is created by what you do today, not tomorrow.

## Skills
* HTML5, CSS3
* Basic knowledge of JavaScript and Git
* Experience of working with Adobe Photoshop and Adobe Illustrator
* C/C++

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
<div class="wrap">
    <div class="video-section">
        <video class="birds" poster="./assets/img/video-birds.png" controls></video>
        <video class="birds-mobile" poster="./assets/img/birds-mobile.png" controls></video>
        <div class="cool-min">
            <div class="cool">the cool<br/>
                <span class="min">the minimal</span>
            </div>
        </div>
    </div>
</div>

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

.icon-area {
    height: 211px;
    background-image: url(./assets/img/icon-area-bg.png);
    background-repeat: no-repeat;
    background-size: 100% 567px;
}

.icon-area .wrap {
    display: flex;
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

void Manager::deleteAllStudents() {
    currentStudentSize = 0;
    cout « "All students have been successfully deleted"« endl;
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
* Landing page in CMS WordPress
* Coursework in the language C++
* Labs from university
* Tasks on Codewars: https://www.codewars.com/users/KarinaMasalova
* Landing page THEYALOW

## Education
* The Academy of Public Administration under the aegis of the President of the Republic of Belarus (Management of Information Resources)
* Educational practice in web studio
* Online courses on Codeacademy: https://www.codecademy.com/users/karinamasalova/achievements
* Participating in Drupal Camp Belarus 2019
* Lectures of IT-Academy and Adukar.by

## English
My English level is B1. I have had an experience of communicating with native speaker. It was a Contribution Day on Drupal Camp Belarus 2019, where I was engaged in translation of technical documentation (it was Umami program).