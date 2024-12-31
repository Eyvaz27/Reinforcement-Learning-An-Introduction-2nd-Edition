# Reinforcement-Learning-An-Introduction-2nd-Edition
Reinforcement Learning: An Introduction 2nd Edition Richard Sutton and Andrew Barto; Exercise Solutions and Programming Materials

Use the following commands to activate the virtual environments:
- python -m pip install --no-cache-dir --upgrade pip
- python -m pip install --no-cache-dir --upgrade pipenv
- pipenv install numpy pandas matplotlib seaborn scikit-learn flask gunicorn -d --skip-lock
- pipenv run python -m pip freeze > requirements.txt && pipenv --rm && \
    pipenv install -r requirements.txt && pipenv lock && pipenv shell