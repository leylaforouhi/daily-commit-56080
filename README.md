def count_digits(number):
    return len(str(abs(number)))

if __name__ == "__main__":
    num = 123456
    print(f"Number of digits in {num}: {count_digits(num)}")
