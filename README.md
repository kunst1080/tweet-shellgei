# tweet-shellgei
Tweet your command line with hashtag "#シェル芸".
(from STDIN)

Usage   : show-current-cmdline | tweet-shellgei

# Getting Started
1. Copy "twitter.key.sample" to your home.

  ```bash
  cp twitter.key.sample $HOME/twitter.key
  ```

2. Get your OAuth access token.

  fight!

3. Edit "twitter.key".

4. Setup alias.

  ```bash
  alias show-current-cmdline='history -p !!'
  ```

5. Tweet!

  ```bash
  show-current-cmdline | tweet-shellgei
  ```
