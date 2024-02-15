# Solana SPL Token Trading Bot


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

### Prerequisites

1. **Solana Wallet:**
   - Ensure you have a Solana wallet with sufficient funds for trading and transaction fees.

2. **Environment:**
   - .

3. **Dependencies:**
   - **SolNet:**
   - **Function:** SolNet is a C# library designed for interacting with the Solana blockchain. It provides functionality for creating and signing transactions, querying account information, and working with the Solana RPC API. SolNet facilitates the integration of Solana blockchain features into C# applications, making it easier for developers to build Solana-compatible tools and bots.

   - **Newtonsoft.Json:**
   - **Function:** Newtonsoft.Json, also known as Json.NET, is a widely used JSON library for C#. Its primary purpose is to handle the parsing and generation of JSON data. In the context of a trading bot, Newtonsoft.Json may be employed to manage communication with Solana nodes or other external APIs that return data in JSON format. It simplifies the serialization and deserialization of JSON objects, making it a valuable tool for data exchange in a standardized format.

   - **.NET Framework 4.8:**
   - **Function:** The .NET Framework 4.8 is the runtime framework for your C# application. It provides a comprehensive set of libraries and runtime components for developing and executing Windows applications. The choice of .NET Framework 4.8 suggests that your trading bot is designed to run on Windows environments and leverages the features and capabilities offered by this specific version of the .NET Framework.

   - **Nethereum:**
   - **Function:** Nethereum is a .NET integration library tailored for Ethereum. While not directly related to Solana, it is included in your dependencies list. If your trading bot interacts with Ethereum-based contracts or features, Nethereum provides the necessary tools for connecting, querying, and interacting with the Ethereum blockchain. It streamlines Ethereum-related operations within a C# application, offering functionalities such as smart contract interaction and transaction handling.

### Configuration

1. **Configure Wallet:**
   - Provide your Solana wallet address and private key in the configuration file.

2. **Set Trading Parameters:**
   - Adjust transaction priority, AutoBuy settings, buy/sell buttons, and slippage in the configuration file.

3. **Token Pair Information:**
   - Specify the SPL token pairs you want to trade.

## Usage

1. **Run the Bot:**
   - Execute the bot script with the command ``.

2. **Monitor Console Output:**
   - Review the console output for transaction details, status, and any potential errors.

3. **Interact with Buy/Sell Buttons:**
   - Utilize the configured buy and sell buttons to execute trades manually.

4. **Automated Trading:**
   - Enable the AutoBuy feature for hands-free trading based on predefined criteria.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This bot comes with no guarantees or warranties. Use it at your own risk, and be aware of potential risks associated with automated trading on the blockchain.

