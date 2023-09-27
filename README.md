# Text-message-decoder

Text Message Decoder
This C++ program is designed to take user input, search for common text message abbreviations, and decode them to their full meanings. It utilizes getline() for input and find() to identify and decode abbreviations. Below are the instructions and usage examples.

### Instructions

1. Get User Input
   The program will prompt you to enter a line of text. It will then display the entered text.

```
Enter text:
IDK if I'll go. It's my BFF's birthday.
You entered: IDK if I'll go. It's my BFF's birthday.
```

2. Search and Decode Abbreviations
   The program will search for common abbreviations in the entered text and provide their decoded meanings. It supports the following abbreviations:

BFF: best friend forever
IDK: I don't know
JK: just kidding
TMI: too much information
TTYL: talk to you later

```
Enter text:
IDK if I'll go. It's my BFF's birthday.
You entered: IDK if I'll go. It's my BFF's birthday.
BFF: best friend forever
IDK: I don't know
```

How to Use

1. Compile the program using a C++ compiler (e.g., g++).

```
g++ main.cpp -o main
```

2. Run the program.

```
./main
```

3. Follow the on-screen prompts to enter your text.

# Example

```
Enter text:
OMG, TMI! LOL, IDK what to do!
You entered: OMG, TMI! LOL, IDK what to do!
TMI: too much information
IDK: I don't know
```

Feel free to add more abbreviations and their meanings to the program as needed.
