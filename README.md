# beam-beam
Experiment with Beam SDK
# Run first example
Runs Beam in the direct runner. Take a sample.txt file to be created in the project directory.

```
mvn compile exec:java -Dexec.mainClass=org.apache.beam.examples.WordCount \
    -Dexec.args="--inputFile=sample.txt --output=counts" -Pdirect-runner
```
