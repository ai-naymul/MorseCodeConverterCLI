# MorseCodeConverterCLI
MorseCodeConverterCLI is a Python command-line program that transforms any text input into Morse Code. Users enter text, and the program converts it to Morse Code, displaying the result in the command line. This project enhances your Python skills while exploring the world of Morse Code communication.

## How to Use

1. Clone this repository to your local machine.
2. Navigate to the directory containing `main.py`.
3. Run the program using Python by typing `python main.py` in your terminal.
4. When prompted, enter a string that you want to convert to Morse code.
5. The program will output your string in Morse code.

## Input

The program accepts any string composed of the English alphabet (both uppercase and lowercase), numbers from 0-9, and spaces.

## Output

The output will be a string of Morse code. Each letter/number is separated by a space, and each word is separated by a slash (`/`).

## Example

Input: `Hello World`

Output: `.... . .-.. .-.. --- / .-- --- .-. .-.. -..`

## Error Handling

If you enter a character that is not in the Morse code dictionary (such as a special character), the program will print "Please enter a valid string" and stop.

## Note

This program does not handle punctuation. If you need to convert punctuation to Morse code, you will need to add those characters to the Morse code dictionary in `main.py`.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.