const dictionary = {
    'dog': 'kutta',
    'cat': 'billi',
    'hi': 'hello',
    "mouse": "माउस",
    "monitor": "मॉनिटर",
    "internet": "इंटरनेट",
    "website": "वेबसाइट",
    "database": "डेटाबेस",
    "algorithm": "एल्गोरिथ्म",
    "calendar date": "कैलेंडर तारीख",
    "calendar view": "कैलेंडर दृश्य"
    // Add more words as needed
};

function searchDictionary() {
    const userInput = document.getElementById('question').value.trim().toLowerCase();

    if (userInput in dictionary) {
        document.getElementById('resulti1').innerText = dictionary[userInput];
    } else {
        for (const key in dictionary) {
            if (dictionary[key].toLowerCase() === userInput) {
                document.getElementById('resulti1').innerText = key;
                return;
            }
        }
        document.getElementById('resulti1').innerText = 'Word not found';
    }
}
