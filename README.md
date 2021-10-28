var alphabet = "абвгдеёжзийклмнопрстуфхцчшщъыьэюя";
var randomString = ""
while (randomString.length <= 8) {
        Math.floor(Math.random() * alphabet.length);
        alphabet[Math.floor(Math.random() * alphabet.length)];
        randomString += alphabet[Math.floor(Math.random() * alphabet.length)];
};
console.log(randomString);
