# Sergii Lukash
## Search Engine Optimization Specialist
### Contact information:
Phone: +38 050 9902641
E-mail: serginata@gmail.com
### Briefly About Myself:
* higher technical education
* Over 10 years experience in SEO
* Successful experience in optimizing websites
* Excellent knowledge of HTML (Hypertext Markup Language) / CSS (Cascading Style Sheets)
* excellent knowledge of SEO tools (screaming frog seo spider, etc.)
* basic knowledge of PHP, Python, Ruby, JavaScript
* good knowledge of Bitrix, Wordpress, Joomla, OpenCart platforms
### Code examples
```javascript
var printMultipleTimes = function (howManyTimes, whatToDraw) {
    for (var i=0; i<howManyTimes; i++) {
        console.log(i + " " + whatToDraw)
    }
};

printMultipleTimes(5, "^_^");

// Створюємо масив із слів
var words = ["javascript", "monkey", "amazing", "pancake", "python", "angular", "mongodb", "node"];

// Обираємо випадкове слово
var word = words[Math.floor(Math.random() * words.length)];

// Встановлюємо масив відповідей
var answerArray = [];
for (var i=0; i<word.length; i++) {
    answerArray[i] = "_";
}

// ігровий цикл
var remainingLetters = word.length;
var attemptNumbers = 10;

while (remainingLetters > 0 && attemptNumbers > 0) {
    // Show the player their progress
    alert(answerArray.join(" "));
    // Take input from the player
    var guess = prompt("Guess a letter, or click Cancel to stop playing.").toLowerCase();
    attemptNumbers--;
    if (guess === null) {
        break;
    }
    else if (guess.length !== 1) {
        alert("Please enter a single letter.");
    } else {
        // Update answerArray and remainingLetters
        for (var j=0; j<word.length; j++) {
            if (word[j] === guess && answerArray[j] === "_") {
                answerArray[j] = guess;
                remainingLetters--;
            }
        }
    }

    // for every correct guess
}

if (remainingLetters === 0) {
    alert(answerArray.join(" "));
    alert("Good job! The answer was " + word);
} else if (attemptNumbers === 0) {
    alert("Спробуй ще!");
}
```
### Courses:
* Node.js, Express, MongoDB & More: The Complete Bootcamp
### Languages:
* knowledge of English at the pre-intermediate level