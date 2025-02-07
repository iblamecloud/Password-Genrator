# Password-Genrator
A Python script designed as part of a cybersecurity project to generate strong and secure passwords with a mix of uppercase, lowercase, digits, and special characters.

## Features:
- Generates a random password with a default length of 12 characters.
- Ensures at least one uppercase letter, one lowercase letter, one digit, and one special character.
- Allows custom password length.
- Uses Python's built-in random and string modules.

## How to use: 
- Clone the repository
- Run the script:
  ```bash
  python password_generator.py
  ```
- Modify password_length to generate a password of your desired length:
  ``` bash
  password_length = 16  # Change this value as needed
  generated_password = generate_password(password_length)
  print(f"Generated password: {generated_password}")
  ```
## Example Output
```bash
Generated password: A8f@G$2hT9q!xY
```

## License
This project is licensed under the MIT License.
