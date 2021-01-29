## Customers Phonebook
    This project provides a customers phonebook sample containing names and phone numbers
    Customers are categorized using the phone number as per the country code, and weather the number is valid or invalid

### Usage and Testing
    - Approach 1: Run `docker-compose up --build` to build both projects
    - Approach 2.1: Open ./customer-api using springboot supporting IDE "preferred eclipse" and run project or test cases
    - Approach 2.2: After running the backend, follow the readme in ./customers-list to run React app

### Content
    ├── customer-api                # Springboot app to provide the filtered data
    |       ├── sample.db           # sqlite db file containing sample data
    ├── customers-list              # react app to provide simple interface
    ├── docker-compose.yml          # to be used to run both react and springboot applications 