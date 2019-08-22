# Online Book Shop Portal
## Table 1: books
| Sno | Name | Category | Price | Rating | Available_Status |
| -- | -- | -- | -- | -- | -- |
| 1 | Java | CS | 450 | 4 | Y |
| 2 | C++ | CS | 200 | 3 | Y |
| 3 | Rose | Story | 100 | 2 | Y |
| 4 | Winners | GK | 150 | 1 | N |
| 5 | Talent | GK | 200 | 4 | Y |

### List All Books
select * from books;

### Popularity of Books
select Name,Price,Rating,Available_Status from books where catogory=? order by rating ASC;


