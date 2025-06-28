# Arabic Spell Checker  

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  

A Python-based spell-checker for Arabic words that suggests corrections for misspelled words using **Levenshtein distance** and a built-in dictionary.  

## Features  
- **Arabic Language Support**: Handles common Arabic words with a built-in dictionary (110+ words).  
- **Levenshtein Algorithm**: Calculates edit distances to find the closest matching words.  
- **Interactive CLI**: Users input a word and receive ranked suggestions (e.g., `قلم` for `قلم`).  
- **Customizable**: Supports external dictionary files (optional).  

## Installation  
1. Clone the repository:  
   
   git clone https://github.com/your-username/repo-name.git
   cd repo-name

## Usage
Launch the spell-checker:

python nlp_2.ipynb
Enter an Arabic word (e.g., حيات → suggests الحياة with distance 1).

Type خروج to exit.

## Example Output

أدخل كلمة للتصحيح (أو 'خروج' للخروج):  
الاقتراحات:  
1. الحياة (المسافة: 1)  
2. السلام (المسافة: 3)  
## Contributing
Contributions welcome!

Add more words to the dictionary.

Improve the algorithm (e.g., phonetic matching).

## License
MIT

**Notes**:  
- Replace `your-username/repo-name` with your GitHub details.  
- For external dictionaries, modify `load_arabic_dictionary(file_path)` to point to your `.txt` file.  
- Mention `pip install jupyter` if users need to run the notebook.  

