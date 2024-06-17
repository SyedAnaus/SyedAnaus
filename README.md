# Hi there, I'm Baymax's Buddy! ![Baymax waving](https://i.pinimg.com/originals/13/88/cf/1388cf9a7b76e6151d1bf5ff16aca454.gif)

![Baymax GIF](https://media.tenor.com/hF3Qutq3gj0AAAAM/baymax.gif)

```bash
> I am Anaus, your personal healthcare companion.
> Let's code and play together!

⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣀⣀⡀⠀
⠀⠀⠀⠀⠀⣀⡤⠶⠒⠶⢤⡀⠀⡴⠋⠀⠀⠙⡆
⠀⠀⠀⠀⡼⠁⠀⠀⠀⣠⠀⠹⡶⠁⠀⠀⠀⠀⡇
⠀⠀⠀⠀⡇⠀⠓⠀⠀⠀⠀⣠⠁⠀⠀⠀⠀⡼⠁
⠀⠀⠀⢀⠽⠦⠤⠤⠤⠐⠊⠀⢣⠀⢀⣠⠞⠀⠀
⠀⠀⣴⠁⠸⠀⠀⠀⠀⠀⠢⠀⠀⡞⠉⠀⠀⠀⠀
⠀⡜⠈⡰⢁⠀⠀⠀⠀⠀⠀⠀⠠⠹⡄⠀⠀⠀⠀
⢸⠁⢠⠃⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⢻⠀⠀⠀⠀
⢸⠀⠸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⠁⠀⠀⠀
⠸⡀⠀⠱⢄⠀⠀⠀⠀⠀⠀⠀⠀⣠⡏⠀⠀⠀⠀
⠀⠙⠤⠴⡆⠉⠒⠂⠠⡄⠐⠒⠉⢸⠇⠀⠀⠀⠀
⠀⠀⠀⠀⠱⣄⠀⠀⣸⢧⡀⢀⣠⠏⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠈⠉⠋⠁⠈⠉⠉⠁⠀⠀⠀⠀⠀⠀

- **Languages**: ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- **Frameworks**: ![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
- **Tools**: ![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

- **Email**: syed.anaus@gmail.com 

### Guess the Number Game
Try to guess the number I'm thinking of between 1 and 100!

```python
import random

def guess_the_number():
    number = random.randint(1, 100)
    guess = None
    while guess != number:
        guess = int(input("Enter your guess: "))
        if guess < number:
            print("Too low! Try again.")
        elif guess > number:
            print("Too high! Try again.")
    print("Congratulations! You've guessed the number.")

if __name__ == "__main__":
    print("Hello, I am Baymax. Let's play a game!")
    guess_the_number()

