# IADB - Championship

## Running the championship

1. In the IADB project repository, run `mvn clean install`.
2. Modify the `src/main/scala/Main.scala` to define the championship you want to launch.
3. In the championship project (where this file is located), run `mvn -q exec:java -Dexec.mainClass=Main > results.md`

## Results

The results are located in `championships/weekXX` folder (for `weekXX` championship) and in the `results.md` file you created just before.

The files located in `championships/weekXX` can be used to visualize the results or to explore the Run history whereas the `results.md` describes the final results of the Run.


