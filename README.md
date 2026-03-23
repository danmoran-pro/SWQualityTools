# Software Development Tools

This repository's functionality depends on the [Apache Ant](https://ant.apache.org) build automation tool having already been installed.

## Usage Notes

Replace the source code in the [src](src) directory with the code you would like to document and analyze.

Test class names are recognized by the suffix "Test" (e.g., MainTest.java for tests of Main.java).

### Invoking and Reviewing
All documentation and analysis tools:
`ant` or `ant all`

View all results:
open the top-level index.html file in a browser window

Suppress most terminal messages, add -q or -quiet :
`ant -q` or `ant -q all`

List all available build targets:
`ant -p`

Invoke a specific target, such as 'test':
`ant test` or `ant -q test`

## Tools Included
This repository supports the following software development tools:
- <a href="https://checkstyle.sourceforge.io">Checkstyle</a> - Coding standard checker
- <a href="https://www.jacoco.org/jacoco/trunk/doc/">JaCoCo</a> - Code test-coverage and complexity reporter
- <a href="https://docs.oracle.com/en/java/javase/26/docs/specs/man/javadoc.html">Javadoc</a> - API documentation generator
- <a href="https://junit.org">JUnit</a> - Unit testing framework
- <a href="https://pmd.github.io">PMD &amp; CPD</a> - Code weakness and duplication scanner
- <a href="https://spotbugs.github.io">SpotBugs</a> - Bytecode-level bug finder

---
SW Quality Tools provides learners with access to documentation and analysis tools.

Copyright &copy; 2011,2026 Dr. Jody Paul

This program is free software: you can redistribute it and/or modify
it under the terms of the [GNU General Public License](LICENSE) as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
