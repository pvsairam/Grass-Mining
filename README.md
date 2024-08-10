# GRASS Mining Script

## Register here 

```bash
https://app.getgrass.io/register/?referralCode=pgSAk6D854mDWlN
```

Python script to automatically run grass mining using a WebSocket proxy.

## Installation

1. Make sure you have Python installed on your Ubuntu VPS system. If not, you can install it with the following command:

    ```bash
    sudo apt update
    sudo apt install python3
    ```

2. Clone this repository to your VPS:

    ```bash
    git clone https://github.com/pvsairam/grass-mining.git
    cd grass-mining
    ```

3. Install the necessary modules using pip:

    ```bash
    pip install -r requirements.txt
    ```

4. You need to install screen to run the script in the background. If not installed, do so with the command:

    ```bash
    sudo apt install screen
    ```

## Usage

1. Make sure you are logged into Grass through your browser before running the script.

2. Run the main script with the following command:

    ```bash
    python main.py
    ```

3. Follow the instructions that appear in the terminal to choose the proxy URL and enter your User ID.

4. The bot will automatically start grass mining using the selected proxy.

## Running the Script in the Background Using Screen

If you want to run the script in the background so you can exit the terminal without affecting the script process, you can use `screen`.

1. Create a new `screen` session with a specific session name:

    ```bash
    screen -S grass
    ```

2. Run the script inside the newly created `screen` session:

    ```bash
    python main.py
    ```

3. Press `Ctrl + A`, then press `D` to return to the main terminal prompt. The script will continue running in the background.

4. To return to the `screen` session and see the script output, use the following command:

    ```bash
    screen -rd grass
    ```

## Retrieving the Grass UID

### PC Users (Chrome)

1. Make sure you are logged into Grass through your Chrome browser.

2. Open the Chrome console by pressing `Ctrl + Shift + J` or `Cmd + Option + J` on macOS

3. Paste the following code into the Chrome console and press Enter:

    ```javascript
    console.log(localStorage.getItem('userId'));
    ```

4. You will see the Grass UID in the Chrome console.

### Mobile Users

1. Make sure you are logged into Grass through your mobile browser.
2. Open the browser developer tools by tapping the menu icon (usually three dots or lines) and selecting the "Developer tools" or "Developer mode" option.
3. Choose the "Console" or "Javascript Console" option.
4. Paste the following code into the console and press Enter:

    ```javascript
    console.log(localStorage.getItem('userId'));
    ```
5. You will see the Grass UID in the mobile browser console.

## Join Our Channel

Join our channel at [OG Airdrop] (https://t.me/Airdrop_OG_Hub) to get the latest updates on airdrops and other exciting promotions!

## Contribution

You can contribute to the development of this script by submitting a pull request or reporting an issue in the [GitHub repository] (https://github.com/pvsairam/grass-mining.git).
