# Kirill Lobanov [<img src="https://avatars.githubusercontent.com/u/24450360?v=4" width="100" style="border-radius: 50%;" />](https://avatars.githubusercontent.com/u/24450360?v=4)

## Contacts

- **Phone**: [+7 917 802 41 41](tel:+79178024141)
- **Telegram**: [@lobanovkirill_ru](https://t.me/lobanovkirill_ru)
- **Email**: [kirill@lobanovkirill.ru](mailto:kirill@lobanovkirill.ru)
- **GitHub**: [https://github.com/lobanovkirill](https://github.com/lobanovkirill)

## About Me

I'm 31 years old, sometimes part time work like freelancer web developer. I have experience working with extra tight deadlines for software development.

## My strengths

- Quick learner
- Team player
- Diligence
- Fast work with deadlines

## Code Examples

**Duplicate Encoder KATA from Codewars.**

The goal of this exercise is to convert a string to a new string where each character in the new string is "(" if that character appears only once in the original string, or ")" if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate.

##### Examples

```

"din"      =>  "((("
"recede"   =>  "()()()"
"Success"  =>  ")())())"
"(( @"     =>  "))(("

```

##### My solution for this task

```

function duplicateEncode(word){
    let arrWord = [...word.toLowerCase()];
    let tempArr = [];

    return arrWord.map((char, idx, arr) => {
      if (arrWord.filter(tempChar => tempChar === char).length > 1) return ')';
      else return '(';
    }).join('');
}

```

## Skills and Proficiency

- HTML5, CSS3 (Bootstrap Framework)
- JavaScript Basics
- PHP (basic knowledge)
- Python (basic knowledge)
- SQL (basic knowledge - SELECT, INSERT, UPDATE, CREATE etc.)
- Git (remote service GitHub)
- Figma (for web development)
- Editor: VSCode
- OS: MacOS, Linux (Ubuntu)
