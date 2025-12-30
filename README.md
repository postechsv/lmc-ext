# lmc-ext
Extension of Maude Logical Model Checker (https://maude.cs.illinois.edu/tools/lmc/)

## Running Benchmarks

To run any benchmark (e.g., `bakery.maude`), you need to ensure `symbolic-checker.maude` is accessible to Maude.

1. **Prerequisites**:
   - Install [Maude 3.3](http://maude.cs.illinois.edu/w/index.php/Maude_download_and_installation) or higher.
   - Copy `src/symbolic-checker.maude` to your Maude installation directory (or any directory in your `MAUDE_LIB` path).

2. **Execution**:
   Navigate to the `benchmarks` directory and run the desired benchmark:
   ```bash
   cd benchmarks
   maude bakery.maude
   ```
