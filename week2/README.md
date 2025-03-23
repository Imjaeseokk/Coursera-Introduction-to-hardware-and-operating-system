# Introduction to Hardware and Operating System

Coursera - IBM

Link to [Course](https://www.coursera.org/learn/introduction-to-hardware-and-operating-systems/)



## Common Computing Devices and Their Components

### Learning Objectives
- Identify common stationary computing devices
- Identify common mobile computing devices
- Describe IoT devices and their applications
- Recognize operating systems used by these devices

---

### Common Computing Devices and Categories

Computing devices are categorized into three types:

- Stationary Devices
- Mobile Devices
- IoT Devices

---

### Stationary Devices

Stationary computing devices include desktops, servers, and gaming consoles. They typically remain fixed in one location, like desks or server racks, and feature:

- Processors
- Memory (RAM)
- Storage
- Input/Output ports (I/O)
- Network connections

#### Workstations (Personal Computers)
- Contain motherboards with CPU, RAM, storage, expansion slots
- Connect peripherals: monitors, keyboards, mice, printers, speakers
- Support upgrades (memory, storage, graphics cards)

#### Servers
- Manage network resources (data storage, email, print jobs)
- Ensure continuous data access with fault-tolerance (multiple servers containing the same data)

#### Desktop Gaming Consoles
- Optimized hardware for gaming
- Include dedicated graphics processors and wireless connectivity
- Typically not upgradeable

---

### Mobile Devices

Mobile devices such as laptops, tablets, and smartphones provide portable computing power.

#### Laptops
- Operating systems: Microsoft Windows, macOS, Linux
- Hardware: CPU, RAM, storage, input/output ports, wireless capabilities
- Generally offer limited upgrades (storage, memory)

#### Tablets
- Operating systems: Windows, iOS, Android, Chrome
- Compact devices, usually without physical keyboards
- Limited storage and ports
- Generally not upgradeable

#### Mobile Phones
- Use mobile-optimized operating systems (Android, iOS)
- Include communication technologies: cellular networks, Wi-Fi, Bluetooth, NFC
- Components are integrated, preventing upgrades

---

### IoT Devices

Internet of Things (IoT) devices are everyday objects equipped with sensors, connectivity, and computing capabilities to exchange data through networks.

- Examples: Smart bulbs, thermostats, wearable devices, medical equipment, smart speakers
- Usually connected via Wi-Fi, Bluetooth, or other wireless standards
- Hardware typically not upgradeable due to integrated design

#### IoT Device Examples:
- Smart home: thermostats, cameras, door locks
- Health: wearable monitors, glucose meters
- Industrial: smart meters, environmental sensors

---

### Operating Systems by Device Category

| Device Category | Operating Systems Used                  |
|-----------------|-----------------------------------------|
| Stationary      | Windows, Linux, macOS                   |
| Mobile          | Windows, macOS, Linux, Android, iOS     |
| IoT Devices     | Lightweight OS or custom embedded systems |

- Stationary devices offer the greatest potential for upgrades.
- IoT devices offer the least or no upgrade options due to integrated components.


## Understanding How Computers Talk

### Learning Objectives
- Describe common notational systems (binary, decimal, hexadecimal)
- Convert numbers between notational systems (binary, decimal, hex)
- Identify common data types and character encoding methods

---

### Common Notational Systems
Computers communicate and store data using specific notational systems. The three primary notations are:

- **Decimal (Base 10)**: Uses digits 0-9. Examples: 1, 10, 100.
- **Binary (Base 2)**: Uses digits 0 and 1, representing on/off states.
- **Hexadecimal (Base 16)**: Uses digits 0-9 and letters A-F (10-15), providing compact representation for larger numbers.

---

### Binary Numbers
#### Bits and Bytes
- **Bit**: Smallest unit of computing data, a single binary digit (0 or 1).
- **Byte**: Consists of eight bits.

#### Decimal to Binary Conversion
To convert decimal numbers to binary:

1. Divide the decimal number by 2 repeatedly.
2. Record the remainder (0 or 1) each time.
3. Continue until the quotient reaches zero.
4. Write remainders from last to first.

Example: Decimal 25 → Binary: `11001`

#### Binary to Decimal Conversion (Doubling Method)
To convert binary numbers to decimal:

- Move from left to right, doubling previous totals and adding the current digit.

Example: Binary `11001` → Decimal `25`

---

### Hexadecimal Notation (Base 16)
Hexadecimal (hex) numbers use digits `0-9` and letters `A-F` to represent values from `10-15`. It is compact and used for:

- MAC addresses (network addresses)
- Color values
- IP addresses
- Memory addresses

#### Hex to Binary Conversion
To convert hex (e.g., `123A`) to binary:

1. Convert each hex digit to a 4-bit binary number.
2. Combine all binary groups.
3. Remove unnecessary zeros on the left.

**Example**:  
`123A` → `0001 0010 0011 1010` → binary: `1001000111010`

---

### Common Data Types
Computers process and present information using these data types:

- **Character**: Single letter or symbol (e.g., 'A')
- **String**: Combination of characters (e.g., "Hello")
- **Integer**: Whole numbers (e.g., 8, -3)
- **Float**: Numbers with decimals or fractions (e.g., 3.14)
- **Boolean**: True or false, yes or no values

---

### ASCII and Unicode
- **ASCII (American Standard Code for Information Interchange)**:
  - Encodes text using 7-bit binary, standard for English characters.
  - Expanded version includes 8-bit encoding.

- **Unicode**:
  - Includes ASCII and additional global characters, symbols, and emojis.
  - UTF-8 encoding is widely used on web pages (over 95% usage globally).
  - UTF-16 often used in programming languages.
  - Represented as hexadecimal notation.

---

### Summary of Key Points
- **Notational Systems**: Decimal, Binary, and Hexadecimal are key to computer communication.
- **Conversions**:
  - Decimal ↔ Binary
  - Hexadecimal ↔ Binary
- **Data Types**: Characters, Strings, Integers, Floats, Boolean values.
- **Character Encoding**: ASCII for basic characters; Unicode (UTF-8 and UTF-16) for broader global text encoding.




