# Convert a String input to Sentence Case


String toSentenceCase(String input) {

  if (input.length() == 0) return input; // Return if the string is empty

  input.toLowerCase();                   // Convert the entire string to lowercase
  
  input[0] = toupper(input[0]);          // Capitalize the first character
  
  return input;

}
