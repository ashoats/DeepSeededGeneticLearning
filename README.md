# Deep Seeded Genetic Learning
## Dependencies
-Python 3
> $ sudo apt-get update
> $ sudo apt-get install python3.6

-OpenAIGym
> $ pip install gym

-PyTorch
> $ pip3 install torch torchvision

-MuJoCo
(Source: https://github.com/openai/mujoco-py/)
1. Obtain a 30-day free trial on the MuJoCo website or free license if you are a student. The license key will arrive in an email with your username and password.
2. Download the MuJoCo version 2.0 binaries for Linux or OSX.
3. Unzip the downloaded mujoco200 directory into ~/.mujoco/mujoco200, and place your license key (the mjkey.txt file from your email) at ~/.mujoco/mjkey.txt.
> $ pip3 install -U 'mujoco-py<2.1,>=2.0'
