# Basic Working Concept of the Enigma Machine

The Enigma Machine is a cipher device used primarily during World War II by Nazi Germany. It was used to encode and decode secret messages. The machine's security relied on a series of rotating disks, or rotors, which would scramble plaintext messages into ciphertext and then reverse the process to decode them.

## Components of the Enigma Machine

1. **Keyboard**: Used to type the plaintext message.
2. **Lampboard**: Displays the encoded or decoded message.
3. **Rotors**: Scramble the letters of the message.
4. **Reflector**: Ensures that encryption is reciprocal.
5. **Plugboard**: Provides additional scrambling by swapping pairs of letters.

## Basic Working Process

1. **Initialization**: The machine is set up with a specific configuration of rotors, reflector, and plugboard settings.
2. **Typing the Message**: The operator types the plaintext message on the keyboard.
3. **Scrambling**: Each key press advances the rotors and scrambles the letter through the plugboard, rotors, and reflector.
4. **Displaying the Ciphertext**: The scrambled letter is displayed on the lampboard.
5. **Decoding**: The process is reversed to decode the message using the same initial settings.

## Example of Encoding and Decoding

### Encoding

1. **Initial Settings**: Rotor positions: A, B, C; Plugboard: A<->Z, B<->Y
2. **Plaintext**: HELLO
3. **Scrambling Process**:
   - H -> R
   - E -> T
   - L -> G
   - L -> G
   - O -> K
4. **Ciphertext**: RTGGK

### Decoding

1. **Initial Settings**: Rotor positions: A, B, C; Plugboard: A<->Z, B<->Y
2. **Ciphertext**: RTGGK
3. **Scrambling Process**:
   - R -> H
   - T -> E
   - G -> L
   - G -> L
   - K -> O
4. **Plaintext**: HELLO

## Diagrams

Below are diagrams to aid understanding of the Enigma Machine's working process.

### Diagram 1: Enigma Machine Components

```
+---------+    +---------+    +---------+    +---------+    +---------+
| Keyboard| -> | Plugboard| -> |  Rotor 1 | -> |  Rotor 2 | -> |  Rotor 3 |
+---------+    +---------+    +---------+    +---------+    +---------+
```

### Diagram 2: Scrambling Process

```
Plaintext -> Plugboard -> Rotor 1 -> Rotor 2 -> Rotor 3 -> Reflector -> Rotor 3 -> Rotor 2 -> Rotor 1 -> Plugboard -> Ciphertext
```
