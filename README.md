# Solana SPL Token Trading Bot
Written tool on C# serves a dual purpose by enabling users to strategically participate in upcoming launches and facilitating the secure acquisition of tokens that are already in circulation. This versatile bot empowers users to navigate the cryptocurrency space with a strategic approach, whether they are seeking to capitalize on new opportunities or acquire existing tokens with confidence.
## Features

1. **Transaction Priority Levels:**
   - Medium: Standard transaction processing time.
   - High: Faster transaction processing with a slightly higher fee.
   - Very High: Expedited transaction processing with a higher fee.

2. **AutoBuy Configuration:**
   - Users can configure the bot to automatically execute buy orders based on predefined criteria.
   - AutoBuy settings include token pair, quantity, and target price.

3. **Buy and Sell Buttons Configuration:**
   - Customize buy and sell buttons with specific parameters.
   - Set the token pair, quantity, and price for each button.

4. **Slippage Configuration:**
   - Adjust slippage tolerance to optimize trade execution.
   - Define acceptable slippage percentages for buy and sell transactions.

## Getting Started
 **Dependencies:**
   - **SolNet:**
   - **Function:** SolNet is a C# library for Solana blockchain interaction. It facilitates transaction creation, signing, and querying account information via the Solana RPC API, enabling seamless integration of Solana features into C# applications.

   - **Newtonsoft.Json:**
   - **Function:** Newtonsoft.Json, a popular JSON library for C#, manages the parsing and generation of JSON data. In the trading bot context, it simplifies communication with Solana nodes or other APIs returning JSON-formatted data.

   - **.NET Framework 4.8:**
   - **Function:** .NET Framework 4.8 serves as the runtime framework for the C# application, providing essential libraries and components for Windows application development.

   - **Nethereum:**
   - **Function:** Nethereum is a .NET library for Ethereum integration. While not Solana-specific, it offers tools for connecting, querying, and interacting with Ethereum, making it useful if the trading bot deals with Ethereum-based contracts or features.

### Configuration

1. **Configure Wallet:**
   - Provide your Solana wallet address and private key in the configuration field.

2. **Set Trading Parameters:**
   - Adjust transaction priority, AutoBuy settings, buy/sell buttons, and slippage in the config field.

3. **Token Pair Information:**
   - Specify the SPL token pairs you want to trade.

## Usage

1. **Clone the repository**
   - Clone the repository and unzip the repository with pass `WxoRgpAX0G` to folder.
     
3. **Run the Bot:**
   - Execute the bot script.

4. **Monitor Console Output:**
   - Review the console output for transaction details, status, and any potential errors.

5. **Interact with Buy/Sell Buttons:**
   - Utilize the configured buy and sell buttons to execute trades manually.

6. **Automated Trading:**
   - Enable the AutoBuy feature for hands-free trading based on predefined criteria.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This bot comes with no guarantees or warranties. Use it at your own risk, and be aware of potential risks associated with automated trading on the blockchain.

