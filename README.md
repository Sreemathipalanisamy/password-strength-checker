PASSWORD STRENGTH CHECKER

This project creates a password strength checker using a Random Forest algorithm. 
The dataset data.csv contains password and strength columns. We clean the data, removing rows with missing or non-string passwords. Features such as length, digits, uppercase, lowercase, and special characters are extracted from each password. The data is split into training and testing sets, and a Random Forest Classifier is trained. The model's accuracy is evaluated, and a function is provided to check the strength of a new password by predicting its strength based on extracted features. Users can enter a password to get its strength rating.
