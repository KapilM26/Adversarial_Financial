# Adversarial_Financial
Reproduction of Adversarial Attacks on Deep Models for Financial Transaction Records

## Steps to run
1. Install requirements
```
pip install -r requirements.txt
```

2. Train models
```
python train_LSTM.py
python train_GRU.py
```

3. Run attacks (adjust model paths in the code)
```
python fsgm_attack.py
python concat_fgsm_attack.py
```