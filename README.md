# PySpark
Eclipse setup
Running Pyspark Code in Eclipse
Building the package
Deploy in Linux Enviornment

# Sample Data Generation

Data Generation script. An utility script helps to do data conversion.

python generateData.py --input /data/nvdcve-2.0-2003.xml \
          --output nvd.jl --format xml --source nvd


python generateData.py --input /data/hackmageddon_20160730.csv \
          --output hackmageddon.jl --format csv --source hackmageddon


python generateData.py --input /data/hackmageddon_20160730.jl \
          --output hackmageddon.jl --format json --source hackmageddon
