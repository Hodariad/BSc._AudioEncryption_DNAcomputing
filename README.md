# Audio Encryption Using DNA State Machine

## Project Overview
This project introduces an innovative audio encryption and decryption algorithm that integrates DNA computing with Moore’s Automaton. It secures audio data by transforming binary audio signals into DNA sequences, encrypting them using DNA-based operations, and reconstructing the original audio file through decryption. The project is implemented using **Mathematica**.

## Features
- **DNA Encryption**: Converts audio data into binary format, then maps it to DNA sequences. A DNA key is generated using the Mersenne Twister algorithm, and Moore’s Automaton is used for encryption.
- **S-Box Transformation**: Adds extra security via S-Box transformations.
- **Decryption**: Uses inverse operations of S-Box and Moore’s Automaton to restore the original audio file.
- **Performance Evaluation**: The algorithm is evaluated for security and efficiency, showing strong resistance to attacks and fast encryption times.

## Files
- `Audio encryption- DNA.nb`: Mathematica notebook implementing the audio encryption and decryption processes.
- `EvalAudio.nb`: Mathematica notebook for evaluating the performance and security of the encryption algorithm.

## How to Run
1. Open **Mathematica**.
2. Load the `.nb` files (`Audio encryption- DNA.nb`, `EvalAudio.nb`).
3. Follow the steps in the notebooks to load an audio file and run the encryption, decryption, and evaluation procedures.

## Requirements
- **Mathematica** (latest version recommended).

## License
This project is open-source and licensed under the MIT License.

## Author
This project was developed by Hoda Ahmed Riad (Hodariad39@gmail.com) under the supervision of professor Mohamed Karam Gabr.
