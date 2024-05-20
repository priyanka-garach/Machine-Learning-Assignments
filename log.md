## Part-1 Small coding assignment
## Solution for Move Method Across Packages Refactoring:
## New git repository created named PYRefDemo
## Changes inside PyRefDemo directory

### New Packages
- Two new packages named `packageOne` and `packageTwo` have been created within the PyRefDemo folder.
- Each package contains one python file. <br/> packageOne contains example1.py <br/> packageTwo contains example_2.py

## Changes inside PyRef directory
### File: refactoring_heuristics.py
- New method `move_method_across_packages(diff_common_element)` has been created.
- Changes have been made in the `move_method_ref()` function to enable a call from the `move_method_across_packages()` function.

### File: diff_code_element.py
- Line 20: Function call changed from `move_method_ref` to `move_method_across_packages`.

## Solution in the form of a code skeleton for Change/Rename Hyperparameter is in file PyRef/CodeSkeleton_ChangeRename Hyperparameter.txt


