# Apache-toree run
1. Install java.
2. Install apache-spark.
3. Set $SPARK_HOME environment variable (Optional).
4. Run following commands:
```bash
python3 -m venv .scala-venv
```
```bash
source .scala-venv/bin/activate
```
```bash
pip install jupyter toree
```
```bash
jupyter toree install --user --spark_home=$SPARK_HOME
```
```bash
jupyter notebook
```

