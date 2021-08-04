# CSV File Challenge - JavaScript/HTML

[Deployed URL 🚀](https://scoperty-csv-fischer.surge.sh/)

Write a JS/HTML program that opens a CSV file from upload, displays it in a text box, processes it, and displays the output in another text box.

The CSV file contains a 2D matrix of numbers where each line holds a single row:

```text
2,4,99,\n
3,55,8,\n
```

## Note:

- I have two csv files for testing purposes because I was unsure as to which format was the appropriate one for sanitizing.

```json
scoperty_test_1: "2,4,99,\n",
scoperty_test_2: [2][4][99]
```

The delimiter can be a space or a single comma. Write the output in same format as input.

Once the input data is read, your application should filter "bad" values. An entry of the matrix is "bad" when it has a value of zero (0). The application should replace these bad values and compute the true value by interpolating it from the surrounding values, i.e., from the spatial neighbors of the entry in the matrix.

[x] Write the matrix with the replaces values to the output text field.

Note: Do not use any 3rd party code or libraries. Use of standard libraries is allowed and encouraged.

---

**Checklist**

[x] Upload csv file

[x] Display raw value from file

[x] Process file to remove bad values

[x] Display sanitized output
