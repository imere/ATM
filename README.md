# Automatic Teller Machine

> 基于Labview的自动取款机的设计

- 初始界面：提示输入卡号和密码，正确则进入操作界面。反之，提示重新输入。卡号和密码请参看“10.csv”文件。
- 卡号和密码输入正确后出现操作界面。其中包含取款，存款，查询功能。
- 取款：输入取款金额，等待计时，取走钱币，显示余额，返回操作界面。如果输入金额大于存有金额，提示错误。
- 存款：放入钱币（可以通过输入框输入），确定，然后显示存入后所有金额总数。
- 查询：显示当前余额。
- 退出：退出后，返回初始界面。

> Design of ATM based on Labview

- Initial interface: prompt to enter the card number and password, and enter the operation interface if correct. Otherwise, prompt to re-enter. For the card number and password, please refer to the "10.csv" file.
- The operation interface appears after the card number and password are entered correctly. It includes withdrawal, deposit, and inquiry functions.
- Withdrawal: Enter the withdrawal amount, wait for the timer, withdraw the coins, display the balance, and return to the operation interface. If the input amount is greater than the existing amount, an error will be prompted.
- Deposit: Put in coins (you can enter through the input box), confirm, and then display the total amount of all the money after deposit.
- Query: Display the current balance.
- Exit: After exiting, return to the initial interface.
