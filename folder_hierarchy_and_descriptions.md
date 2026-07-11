# Python Examples Folder Hierarchy and Description Space

This document provides a simple hierarchy map for the repository and a short description area for each folder so examples can be documented consistently.

## Repository hierarchy

```text
Python-Examples/
├── README.md
├── list_comprehension_examples/                  # Placeholder for list comprehension examples
├── dictionary_comprehension_examples/           # Placeholder for dictionary comprehension examples
├── iterables_application_examples/               # Examples related to iterables and iteration tools
│   ├── generators_examples/                     # Generator-based examples
│   └── basic_iterator_examples/                 # Iterator and iteration protocol examples
├── performance_metrics_examples/                # Placeholder for performance-related examples
├── Errors_and_handeling_examples/               # Placeholder for error handling examples
├── matplotlib_examples/                         # Plotting and visualization examples
│   ├── matplot_images/                          # Saved image outputs from matplotlib scripts
│   └── graph_types/                             # Graph/plot type examples
├── pandas_examples/                             # Placeholder for pandas usage examples
├── decorator_examples/                          # Placeholder for decorator examples
├── regex_examples/                              # Placeholder for regex examples
└── class_examples/                              # Object-oriented programming examples
    ├── inheretence_examples/                    # Inheritance-related examples
    └── overloading_examples/                    # Operator/overloading examples
```

## Folder description space

Use the template below to describe what belongs in each folder.

### Root
- Purpose: Main repository for Python syntax, algorithms, and example code.
- Example focus: General Python concepts and reusable sample scripts.
- Notes: Keep the top-level README updated with major additions.

### list_comprehension_examples
- Purpose: Store examples that demonstrate list comprehension syntax and usage.
- Typical examples: Filtering, transforming, and flattening lists.
- Notes: Add a short description per script explaining the pattern applied.

### dictionary_comprehension_examples
- Purpose: Store examples that demonstrate dictionary comprehension syntax and usage.
- Typical examples: Mapping keys to values, filtering dictionaries, and nested data transforms.
- Notes: Include input/output examples where helpful.

### iterables_application_examples
- Purpose: Collect examples about iteration protocols, generators, and iterable utilities.
- Typical examples: Custom iterators, generator expressions, lazy evaluation.
- Notes: Split examples into subfolders by concept category.

### iterables_application_examples/generators_examples
- Purpose: Contain generator-based examples.
- Typical examples: Yield-based functions, lazy sequences, memory-efficient pipelines.
- Notes: Mention whether the example uses a generator function or generator expression.

### iterables_application_examples/basic_iterator_examples
- Purpose: Contain examples for basic iterator behavior and the iterator protocol.
- Typical examples: __iter__, __next__, manual iteration, iterables vs iterators.
- Notes: Highlight the difference between an iterable and an iterator.

### performance_metrics_examples
- Purpose: Store examples related to timing, profiling, or measuring performance.
- Typical examples: Benchmarking code, comparing algorithms, memory/time measurements.
- Notes: Document the tool or method used for measurement.

### Errors_and_handeling_examples
- Purpose: Store examples for exception handling and error management.
- Typical examples: try/except/finally blocks, custom exceptions, logging errors.
- Notes: Describe the failure case being handled.

### matplotlib_examples
- Purpose: Store visualization examples using matplotlib.
- Typical examples: Line charts, bar charts, scatter plots, and custom styling.
- Notes: Keep image outputs in the subfolder for easy review.

### matplotlib_examples/matplot_images
- Purpose: Store generated image files or visual outputs from plotting examples.
- Typical examples: PNG/JPG screenshots of charts created by scripts.
- Notes: Keep file names descriptive and tied to the source script.

### matplotlib_examples/graph_types
- Purpose: Store examples that demonstrate different plotting graph types.
- Typical examples: Line, bar, histogram, pie, and scatter charts.
- Notes: Group examples by chart type when possible.

### pandas_examples
- Purpose: Store examples using pandas for data analysis and manipulation.
- Typical examples: DataFrames, filtering rows, grouping, merging, and reading CSV/JSON files.
- Notes: Mention the dataset or input format used in each example.

### decorator_examples
- Purpose: Store examples that demonstrate decorators and decorator patterns.
- Typical examples: Function wrappers, logging decorators, timing decorators, class decorators.
- Notes: Explain what the decorator changes in the wrapped function.

### regex_examples
- Purpose: Store examples that demonstrate regular expressions.
- Typical examples: Searching, validating, replacing, and extracting text.
- Notes: Include both the pattern and a sample input/output.

### class_examples
- Purpose: Store object-oriented programming examples.
- Typical examples: Classes, inheritance, polymorphism, encapsulation, and operator overloading.
- Notes: Keep example files grouped by OOP concept.

### class_examples/inheretence_examples
- Purpose: Store examples relating to inheritance and subclass relationships.
- Typical examples: Parent-child class relationships, method overriding, abstract base classes.
- Notes: Clear up which class inherits from which other class.

### class_examples/overloading_examples
- Purpose: Store examples relating to operator overloading or method overloading concepts.
- Typical examples: __add__, __str__, __len__, or custom operator behaviors.
- Notes: Describe the overloaded behavior clearly.

## Suggested usage

1. Add a short description for each new example file.
2. Keep the folder names aligned with the concept being demonstrated.
3. Update this file whenever a new category or subfolder is introduced.
