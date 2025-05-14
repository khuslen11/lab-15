How to Use

To use this Maven-based Java project:
	1.	Clone the repository:
git clone https://github.com/your-username/calculator.git
cd calculator
	2.	Run unit tests using JUnit:
mvn test
	3.	Check code style with Checkstyle:
mvn checkstyle:check
	4.	Generate code coverage report with JaCoCo:
mvn jacoco:report
The report will be available at target/site/jacoco/index.html.
	5.	Run all checks including tests, style checks, and coverage:
mvn verify