# JSON_api
Extracting Data from JSON

In this assignment I wrote a Python program somewhat similar to http://www.py4e.com/code3/json2.py. The program prompted for a URL, read the JSON data from that URL using urllib and then parsed and extracted the comment counts from the JSON data, computed the sum of the numbers in the file and entered the sum below:

Data Format
The data consists of a number of names and comment counts in JSON as follows:

{
  comments: [
    {
      name: "Matthias"
      count: 97
    },
    {
      name: "Geomer"
      count: 97
    }
    ...
  ]
}

Sample Execution

$ python3 solution.py
Enter location: http://py4e-data.dr-chuck.net/comments_42.json
Retrieving http://py4e-data.dr-chuck.net/comments_42.json
Retrieved 2733 characters
Count: 50
Sum: 2...
