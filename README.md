# currency converter 

def convert_currency(amount, exchange_rate):
    return amount * exchange_rate

def main():
    print("Welcome to the Currency Converter!")
    amount = float(input("Enter the amount in USD: "))
    exchange_rate = float(input("Enter the exchange rate: "))

    result = convert_currency(amount, exchange_rate)
    print(f"{amount} USD is equal to {result:.2f} in the target currency.")

if __name__ == "__main__":
    main()
