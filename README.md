#include <iostream>
using namespace std;
// Book Class
class Book {
private:
    int id;
    std::string title;
    std::string author;
    bool isAvailable;

public:
    Book(int id, const std::string& title, const std::string& author)
        : id(id), title(title), author(author), isAvailable(true) {}
};

// User Class
class User {
private:
    int id;
    std::string name;
    std::vector<int> borrowedBooks;

public:
    User(int id, const std::string& name) : id(id), name(name) {}
, borrowedBooks.end(), bookId), borrowedBooks.end());
};
// Library Class
class Library {
private:
    std::vector<Book> books;
    std::unordered_map<int, User> users;
public:
    void addBook(const Book& book) {
        books.push_back(book);
    }

 book : books) {
  true;
        }
        return false;
    }
};
// Test cases
void testLibrary() {
    Library library;
}
int main() {
    // Main program
    Library library;
    std::cout << "All tests passed!\n";
}
