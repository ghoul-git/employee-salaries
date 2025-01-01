# Employee Salaries Project

**Course:** Data Science Programming

**Team Members:**

- Abd Al Rahman Suhaib Al Ghool
- Malek Ramadan Ahmad Al Omari

## Project Details

### Dataset

### Description of all Functions and Classes:
Please find the deatils in the code as documentation

### Input

| Name               | Department  | Salary  | Years in Company | Position     |
|--------------------|-------------|---------|------------------|--------------|
| John Doe           | Sales       | 50000   | 5                | Manager      |
| Jane Smith         | Marketing   | 40000   | 3                | Executive    |
| Bob Johnson        | HR          | 35000   | 2                | Analyst      |
| Alice Brown        | IT          | 60000   | 7                | Manager      |
| Charlie Davis      | Finance     | 70000   | 10               | Executive    |
| David Wilson       | Sales       | 48000   | 4                | Analyst      |
| Eve Moore          | Marketing   | 45000   | 3                | Assistant    |
| Frank Taylor       | HR          | 32000   | 1                | Executive    |
| Grace Anderson     | IT          | 55000   | 6                | Manager      |
| Hank Thomas        | Finance     | 65000   | 8                | Analyst      |
| Ivy Jackson        | Sales       | 51000   | 5                | Assistant    |
| Jack White         | Marketing   | 42000   | 3                | Manager      |
| Karen Harris       | HR          | 33000   | 2                | Analyst      |
| Leo Martin         | IT          | 58000   | 6                | Executive    |
| Mona Clark         | Finance     | 67000   | 9                | Manager      |
| Nathan Lewis       | Sales       | 49000   | 4                | Executive    |
| Olivia Walker      | Marketing   | 46000   | 3                | Assistant    |
| Paul Hall          | HR          | 34000   | 1                | Manager      |
| Quinn Allen        | IT          | 54000   | 5                | Analyst      |
| Rita Young         | Finance     | 66000   | 7                | Executive    |
| Sam King           | Sales       | 53000   | 6                | Manager      |
| Tina Scott         | Marketing   | 47000   | 3                | Analyst      |
| Uma Green          | HR          | 35000   | 2                | Assistant    |
| Victor Adams       | IT          | 59000   | 7                | Manager      |
| Wendy Baker        | Finance     | 68000   | 10               | Executive    |
| Xander Perez       | Sales       | 52000   | 5                | Analyst      |
| Yvonne Carter      | Marketing   | 43000   | 3                | Manager      |
| Zachary Mitchell   | HR          | 31000   | 1                | Executive    |
| Anna Harris        | IT          | 60000   | 6                | Assistant    |
| Ben Collins        | Finance     | 69000   | 8                | Manager      |
| Catherine Murphy   | Sales       | 51000   | 4                | Executive    |
| Daniel Scott       | Marketing   | 44000   | 3                | Analyst      |
| Eva King           | HR          | 33000   | 2                | Assistant    |
| Felix Ward         | IT          | 57000   | 5                | Manager      |
| Gina Bell          | Finance     | 64000   | 7                | Executive    |
| Henry Cox          | Sales       | 55000   | 6                | Manager      |
| Isla Morris        | Marketing   | 45000   | 3                | Assistant    |
| James Cooper       | HR          | 34000   | 2                | Executive    |
| Kimberly Nelson    | IT          | 62000   | 6                | Manager      |
| Louis Mitchell     | Finance     | 65000   | 7                | Analyst      |
| Monica Harris      | Sales       | 54000   | 4                | Executive    |
| Nina Perez         | Marketing   | 47000   | 3                | Manager      |
| Oscar Howard       | HR          | 32000   | 1                | Analyst      |
| Paul White         | IT          | 65000   | 8                | Manager      |
| Quincy Taylor      | Finance     | 70000   | 9                | Executive    |
| Rachel Anderson    | Sales       | 49000   | 5                | Analyst      |
| Sophie Adams       | Marketing   | 43000   | 3                | Assistant    |
| Tom Jones          | HR          | 31000   | 2                | Manager      |
| Ursula Bennett     | IT          | 57000   | 7                | Executive    |
| Victor Roberts     | Finance     | 68000   | 8                | Analyst      |
| Wendy Evans        | Sales       | 52000   | 6                | Manager      |
| Xena Clark         | Marketing   | 46000   | 3                | Executive    |
| Yara Davis         | HR          | 33000   | 2                | Analyst      |
| Zane Moore         | IT          | 62000   | 7                | Manager      |


### Output

| Employee ID | Name               | Department  | Salary  | Years in Company | Position     | Adjusted Salary |
|-------------|--------------------|-------------|---------|------------------|--------------|-----------------|
| 1           | John Doe           | Sales       | 50000   | 5                | Manager      | 72500.0         |
| 2           | Jane Smith         | Marketing   | 40000   | 3                | Executive    | 50000.0         |
| 3           | Bob Johnson        | HR          | 35000   | 2                | Analyst      | 40250.0         |
| 4           | Alice Brown        | IT          | 60000   | 7                | Manager      | 93000.0         |
| 5           | Charlie Davis      | Finance     | 70000   | 10               | Executive    | 112000.0        |
| 6           | David Wilson       | Sales       | 48000   | 4                | Analyst      | 60000.0         |
| 7           | Eve Moore          | Marketing   | 45000   | 3                | Assistant    | 53550.0         |
| 8           | Frank Taylor       | HR          | 32000   | 1                | Executive    | 36800.0         |
| 9           | Grace Anderson     | IT          | 55000   | 6                | Manager      | 82500.0         |
| 10          | Hank Thomas        | Finance     | 65000   | 8                | Analyst      | 94250.0         |
| 11          | Ivy Jackson        | Sales       | 51000   | 5                | Assistant    | 65790.0         |
| 12          | Jack White         | Marketing   | 42000   | 3                | Manager      | 56700.0         |
| 13          | Karen Harris       | HR          | 33000   | 2                | Analyst      | 37950.0         |
| 14          | Leo Martin         | IT          | 58000   | 6                | Executive    | 81200.0         |
| 15          | Mona Clark         | Finance     | 67000   | 9                | Manager      | 110550.0        |
| 16          | Nathan Lewis       | Sales       | 49000   | 4                | Executive    | 63700.0         |
| 17          | Olivia Walker      | Marketing   | 46000   | 3                | Assistant    | 54740.0         |
| 18          | Paul Hall          | HR          | 34000   | 1                | Manager      | 42500.0         |
| 19          | Quinn Allen        | IT          | 54000   | 5                | Analyst      | 70200.0         |
| 20          | Rita Young         | Finance     | 66000   | 7                | Executive    | 95700.0         |
| 21          | Sam King           | Sales       | 53000   | 6                | Manager      | 79500.0         |
| 22          | Tina Scott         | Marketing   | 47000   | 3                | Analyst      | 56400.0         |
| 23          | Uma Green          | HR          | 35000   | 2                | Assistant    | 39900.0         |
| 24          | Victor Adams       | IT          | 59000   | 7                | Manager      | 91450.0         |
| 25          | Wendy Baker        | Finance     | 68000   | 10               | Executive    | 108800.0        |
| 26          | Xander Perez       | Sales       | 52000   | 5                | Analyst      | 67600.0         |
| 27          | Yvonne Carter      | Marketing   | 43000   | 3                | Manager      | 58050.0         |
| 28          | Zachary Mitchell   | HR          | 31000   | 1                | Executive    | 35650.0         |
| 29          | Anna Harris        | IT          | 60000   | 6                | Assistant    | 80400.0         |
| 30          | Ben Collins        | Finance     | 69000   | 8                | Manager      | 110400.0        |
| 31          | Catherine Murphy   | Sales       | 51000   | 4                | Executive    | 66300.0         |
| 32          | Daniel Scott       | Marketing   | 44000   | 3                | Analyst      | 52800.0         |
| 33          | Eva King           | HR          | 33000   | 2                | Assistant    | 37620.0         |
| 34          | Felix Ward         | IT          | 57000   | 5                | Manager      | 82650.0         |
| 35          | Gina Bell          | Finance     | 64000   | 7                | Executive    | 92800.0         |
| 36          | Henry Cox          | Sales       | 55000   | 6                | Manager      | 82500.0         |
| 37          | Isla Morris        | Marketing   | 45000   | 3                | Assistant    | 53550.0         |
| 38          | James Cooper       | HR          | 34000   | 2                | Executive    | 40800.0         |
| 39          | Kimberly Nelson    | IT          | 62000   | 6                | Manager      | 93000.0         |
| 40          | Louis Mitchell     | Finance     | 65000   | 7                | Analyst      | 91000.0         |
| 41          | Monica Harris      | Sales       | 54000   | 4                | Executive    | 70200.0         |
| 42          | Nina Perez         | Marketing   | 47000   | 3                | Manager      | 63450.0         |
| 43          | Oscar Howard       | HR          | 32000   | 1                | Analyst      | 35200.0         |
| 44          | Paul White         | IT          | 65000   | 8                | Manager      | 104000.0        |
| 45          | Quincy Taylor      | Finance     | 70000   | 9                | Executive    | 108500.0        |
| 46          | Rachel Anderson    | Sales       | 49000   | 5                | Analyst      | 63700.0         |
| 47          | Sophie Adams       | Marketing   | 43000   | 3                | Assistant    | 51170.0         |
| 48          | Tom Jones          | HR          | 31000   | 2                | Manager      | 40300.0         |
| 49          | Ursula Bennett     | IT          | 57000   | 7                | Executive    | 82650.0         |
| 50          | Victor Roberts     | Finance     | 68000   | 8                | Analyst      | 98600.0         |
| 51          | Wendy Evans        | Sales       | 52000   | 6                | Manager      | 78000.0         |
| 52          | Xena Clark         | Marketing   | 46000   | 3                | Executive    | 57500.0         |
| 53          | Yara Davis         | HR          | 33000   | 2                | Analyst      | 37950.0         |
| 54          | Zane Moore         | IT          | 62000   | 7                | Manager      | 96100.0         |
