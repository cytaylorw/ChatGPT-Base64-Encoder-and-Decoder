# ChatGPT Base64 Encoder and Decoder

A Base64 Encoder and Decoder written by ChatGPT on 2023/3/27.

## ChatGPT Prompt

```text
You are a Web developer. Please create a web page to encode and/or decode Base64 string with the following requirements and specifications:

General requirements:
- Written only with HTML and pure Javascript
- Users can choose to encode or decode the string
- Users can copy the result to the clipboard

Specifications:
- Align the body at the center
- Put the script at the end
- A title is displayed
- An empty table displayed initially with headers:
    1. Option
    2. Input
    3. Output
- The HTML contains no initial row
- Added the first row after the page is loaded
- Option column contains the encode and decode option
- Input column contains an textarea for string to encode/decode
- Output column contains an textarea for the encoded/decoded string
- The input is parsed upon entering
- The output will be copied to clipboard by clicking or focusing on the output textarea
- Upon copied, create a copied message with pseudo element next to the output textarea for 2 sec
- The copied pseudo element floating on top of the table cell
- An Add button is displayed after the title and before the table to add one row to the table

```

### Notes

- Better to start a new chat when updating requirement/specification
- The copied message is an alert by default.
- Need to tell ChatGPT to what to use for copied message or else it will just append the message to the inner text

## ChatGPT Response code

Please refer to file [index.html](./index.html)
