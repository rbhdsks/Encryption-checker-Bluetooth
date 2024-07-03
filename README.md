# Bluetooth Security Analysis and BlueBorne Vulnerability Implementation

## Project Overview
This project focuses on the security analysis of Bluetooth communication, identifying encryption packets and protocols using Pyshark, and auditing various Bluetooth devices for vulnerabilities. Key components include:

## Key Features
- **Packet Identification:** Utilized Pyshark to identify encryption packets and protocols in Bluetooth communication, specifically via BTHCI protocol and their opcodes.
- **Automation Script:** Developed a Python script to process and pair the identified packets from captured files.
- **Vulnerability Auditing:** Conducted security audits on multiple Bluetooth devices to identify potential vulnerabilities.
- **BlueBorne Implementation:** Implemented and tested the BlueBorne vulnerability on different Bluetooth devices to assess security risks.

## Technologies Used
- Python
- Pyshark
- Bluetooth
- Git & GitHub
- Linux

## Experience Summary
As part of the C3iHub fellowship, I gained hands-on experience in cybersecurity, focusing on Bluetooth communication protocols and vulnerabilities. The project involved developing tools and scripts to automate the identification and analysis of encryption packets, auditing device security, and implementing known vulnerabilities like BlueBorne. This comprehensive analysis enhanced my understanding of Bluetooth security and provided practical insights into cybersecurity practices.

## How to Use
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/rbhdsks/Encryption-checker-Bluetooth/
    cd bluetooth-security-analysis
    ```

2. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Python Script:**
    ```bash
    python analyze_packets.py path_to_your_pcap_file
    ```

4. **Auditing Devices:**
    - Follow the instructions in `AUDIT.md` for detailed steps on auditing Bluetooth devices for vulnerabilities.

## Contributions
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or additional features.

## License
This project is licensed under the c3ihub-IIT Kanpur License. See the `LICENSE` file for details.

## Contact
For any queries or issues, please open an issue in the repository or contact me at [iib2021002@iiita.ac.in].
