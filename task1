function checkPassword(password) {
    const minLength = 8;
    const hasNumber = /[0-9]/.test(password);
    const hasLowerCase = /[a-z]/.test(password);
    const hasUpperCase = /[A-Z]/.test(password);

    
    if (password.length >= minLength && hasNumber && hasLowerCase && hasUpperCase) {
        return "Strong";
    } else {
        return "Weak";
    }
}

console.log(checkPassword("vbvvxnk"));
console.log(checkPassword("Dzsfo13rd"));
