# Search engine

English Wikipedia article search engine. Engine uses Singular Value Decomposition (SVD) to remove noise from the initial matrix and multiplies it by IDF (inverse document frequency) to lower the significance of common words in the text. The current model includes articles from Computing category. Because of the size of the matrix, this repository contains only an IDF matrix.

More about this method: Matrix Analysis and Applied Linear Algebra, Carl D. Mayer, SIAM, 2000. Singular Value Decomposition: Example 5.12.3 and Example 5.12.4

This project was a part of the computational methods course at AGH UST. The project description (in Polish), as well as article pre-processing code, is available [here](https://github.com/pklatka/computational-methods-course/tree/main/Lab%2006).

## How to run

1. Clone the repository
2. Go to server directory
3. Run `npm install`
4. Run `npm start`
5. Go to `http://localhost:3000/` and enjoy!
