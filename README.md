# OWASP-Juice-Shop-Writeup
OWASP Juice Shop is an intentionally vulnerable web application designed to aid in the education and training of cybersecurity professionals, ethical hackers, and penetration testers. It serves as a practical platform for learning about web application security risks by simulating real-world vulnerabilities, including those listed in the OWASP Top Ten. The goal is to finish all the challenges provided in https://pwning.owasp-juice.shop/companion-guide/latest/part2/README.html

## Installation

I personally prefer running this using Docker. Here is how you can do it:

1. Install Docker Desktop and open it.

2. In terminal, run:
   ```bash
   docker pull bkimminich/juice-shop

3. Then run:
   ```bash
   docker run --rm -p 127.0.0.1:3000:3000 bkimminich/juice-shop

4. Browse to http://localhost:3000 (on macOS and Windows browse to http://192.168.99.100:3000 if you are using docker-machine instead of the native docker installation)

