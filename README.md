# Simple Interest Calculator

This project contains a simple Bash script that calculates simple interest based on user input.

## Formula

Simple Interest is calculated using the formula:

Simple Interest = (Principal × Rate × Time) / 100

## Requirements

* Bash shell
* `bc` calculator utility (usually pre-installed on Linux)

To install `bc` if it is missing:

```bash
sudo apt install bc
```

## How to Use

1. Make the script executable:

```bash
chmod +x simple-interest.sh
```

2. Run the script:

```bash
./simple-interest.sh
```

3. Enter the following when prompted:

* Principal amount
* Rate of interest (%)
* Time period (years)

## Example

```
Simple Interest Calculator
--------------------------
Enter Principal Amount: 1000
Enter Rate of Interest (%): 5
Enter Time Period (years): 2

Principal: 1000
Rate: 5%
Time: 2 years
Simple Interest: 100.00
```

## Files

* `simple-interest.sh` – Bash script that calculates simple interest.
* `README.md` – Project documentation.
* `LICENSE` – License information.
* `CODE_OF_CONDUCT.md` – Community guidelines.
* `CONTRIBUTING.md`
