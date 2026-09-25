
- You're about to learn some common denormalization techniques
# Normalized Data

- Organized related fields into different tables, and maintains defined relationships between columns in these different tables.
- When data is normalized, it's generally easier to duplicate data and inconsistences, and apply updates. 

# Denormalized Data

- Stores repeated information in one or more tables

Benefits of denormalized data:

- Ideal for gathering information quickly
- Reduces overall complexity 
- Creates the ability to scale quickly

Disadvantages of denormalized data:

- Duplicated data
- Increased stored needs
- Potential for inconsistences

## Ways to Denormalize Data

- **Add duplicate columns**, then a data analyst doesn't need to join tables
- **Split tables** into smaller once, only have rows and columns that each application needs
- **Mirror tables**, making copies of tables for easy reading
- **Create summary tables** 


























 