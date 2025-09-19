def write_to_file(filename, tet):
    with open(filename, "w") as f:
        f.write(text)

if __name__ == "__main__":
    write_to_file("note.txt", "This is my first file created with Python!")
    print("File 'note.txt' has been created.")
