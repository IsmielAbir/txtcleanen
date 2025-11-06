# txtcleanen

**txtcleanen** is a simple Python package for cleaning English text by removing HTML tags, URLs, emojis, numbers, punctuation, and extra whitespace — ideal for Natural Language Processing (NLP) and text preprocessing tasks.

---

## ✨ Features

- Remove HTML tags  
- Remove URLs  
- Remove emojis  
- Remove digits and punctuation  
- Normalize Unicode text  
- Compact multiple spaces into one  

---

## 🚀 Installation

```bash
pip install txtcleanen
```

## Example
```
import txtcleanen
text = "Hello 😊 <b>World!</b> Visit https://example.com now!"
clean_text = txtcleanen(text)
print(clean_text)
# Output: "Hello World Visit now"
```

