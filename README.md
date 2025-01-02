# Reinforcement-Learning-An-Introduction-2nd-Edition
Reinforcement Learning: An Introduction 2nd Edition Richard Sutton and Andrew Barto; Exercise Solutions and Programming Materials

Below is the brief summary of algorithms we have implemented in different chapters:
- Chapter 2, Multi-Armed Bandit Algorithms 
    - Simple Bandit Algorithm (SBA)
    - SBA with non-stationary environment dynamics
    - SBA with Optimistic Initial Values
    - SBA with Upper-Confidence Bound Action Selection  

Use the following commands to activate the virtual environments:
- python -m pip install --no-cache-dir --upgrade pip
- python -m pip install --no-cache-dir --upgrade pipenv
- pipenv install numpy pandas matplotlib seaborn scikit-learn flask gunicorn -d --skip-lock
- pipenv run python -m pip freeze > requirements.txt && pipenv --rm && \
    pipenv install -r requirements.txt && pipenv lock && pipenv shell