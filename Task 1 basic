class Employee:
    def __init__(self, name, emp_id, salary, department):
        self.name = name
        self.id = emp_id
        self.salary = salary
        self.department = department

    def calculate_salary(self, hours_worked):
        overtime = max(0, hours_worked - 50)
        self.salary += (overtime * (self.salary / 50))

    def assign_department(self, emp_department):
        self.department = emp_department

    def print_employee_details(self):
        print("Name:", self.name)
        print("ID:", self.id)
        print("Salary:", self.salary)
        print("Department:", self.department)
        print("----------------------")

# Example usage:
employee1 = Employee("ADAMS", "E7876", 50000, "ACCOUNTING")
employee2 = Employee("JONES", "E7499", 45000, "RESEARCH")
# ... (add more employees)

# Modify departments and calculate overtime (if eligible)
employee1.assign_department("OPERATIONS")
employee2.calculate_salary(52)  # Assuming 52 hours worked

# Display updated employee details
employee1.print_employee_details()
employee2.print_employee_details()
# ...
