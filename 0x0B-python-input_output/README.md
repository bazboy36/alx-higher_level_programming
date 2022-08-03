# 0x0B. Python - Input/Output
## **Description**
This project is about how to read/write files and working with json files in python

## Table of contents
|Files |	Description|
| ---- | ---- |
|.gitignore |	Ignore test files |
|0-read_file.py |	Function that reads a text file (UTF8) and prints it to stdout: Prototype: def read_file(filename=""): |
|1-write_file.py |	Function that writes a string to a text file (UTF8) and returns the number of characters written: Prototype: def write_file(filename="", text=""): |
|2-append_write.py |	Function that appends a string at the end of a text file (UTF8) and returns the number of characters added: Prototype: def append_write(filename="", text=""): |
|3-to_json_string.py |	Function that returns the JSON representation of an object (string): Prototype: def to_json_string(my_obj): |
|4-from_json_string.py |	Function that returns an object (Python data structure) represented by a JSON string: Prototype: def from_json_string(my_str): |
|5-save_to_json_file.py	|Function that writes an Object to a text file, using a JSON representation: Prototype: def save_to_json_file(my_obj, filename): |
|6-load_from_json_file.py |	Function that creates an Object from a “JSON file”: Prototype: def load_from_json_file(filename) |
|7-add_item.py |	A script that adds all arguments to a Python list, and then save them to a file: |
|8-class_to_json.py |	Function that returns the dictionary description with simple data structure (list, dictionary, string, integer and boolean) for JSON serialization of an object: Prototype: def class_to_json(obj): |
|9-student.py |	A class Student that defines a student by: Instantiation with first_name, last_name and age: def init(self, first_name, last_name, age): |
|10-student.py |	A class Student that defines a student by: (based on 9-student.py) Instantiation with first_name, last_name and age: def init(self, first_name, last_name, age): |
|11-student.py |	A class Student that defines a student by: (based on 10-student.py) Instantiation with first_name, last_name and age: def init(self, first_name, last_name, age): |
|12-pascal_triangle.py |	Function def pascal_triangle(n): that returns a list of lists of integers representing the Pascal’s triangle of n: |
|100-append_after.py |	Function that inserts a line of text to a file, after each line containing a specific string (see example): Prototype: def append_after(filename="", search_string="", new_string=""): |
|101-stats.py |	A script that reads stdin line by line and computes metrics: Input format: - [] "GET /projects/260 HTTP/1.1" |
