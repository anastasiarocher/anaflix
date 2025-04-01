function randomDecision(maximum) {
    if (isNaN(maximum) || maximum < 1) {
        return "Please enter a valid number!";
    }

    let randomNumber = Math.floor(Math.random() * maximum);
    if (randomNumber % 2 === 0) {
        return `The number ${randomNumber} was drawn. Just do it!`;
    } else {
        return `The number ${randomNumber} was drawn. Don't do it, cyka!`;
    }
}

function displayDecision() {
    let max = parseInt(document.getElementById("maxNumber").value);
    document.getElementById("decision").textContent = randomDecision(max);
}
