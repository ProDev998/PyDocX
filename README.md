# PyDocX - Python Documentation eXtractor with Interactive Features

PyDocX - 
PyDocX is a Python library designed to automate the generation of dynamic and interactive documentation for Python projects. It extracts documentation from source code, integrates interactive examples and demos, tracks changes, and supports customizable templates. With PyDocX, developers can create comprehensive and up-to-date documentation that enhances user engagement and understanding.

# Features

1) Automatic Documentation Extraction: This feature automatically extracts documentation from the provided Python module, including docstrings, comments, and type annotations, to create a comprehensive documentation dataset.
2) Display Documentation: It displays the extracted documentation, presenting each documented object's name along with its associated documentation string.
3) Interactive Example: This feature allows users to interactively input data through a text widget and see the output, providing a hands-on experience within the documentation itself.
4) Track Changes: It tracks changes made to the module using Git, allowing users to view modifications made to the source code since the last commit.
5) Search Documentation: This functionality enables users to search for specific keywords or phrases within the extracted documentation, facilitating quick access to relevant information.
6) Generate Customized HTML: It generates customized HTML documentation based on a provided template, allowing users to tailor the documentation's appearance to match their project's branding and style.

# Usage 

This is how to import and use the library. Its a basic example code.

if __name__ == "__main__":
        import pydocx  # Replace with your module name
        generator = DocumentationGenerator(my_module)
        generator.display_documentation()
        generator.interactive_example()
        generator.track_changes()

    # Search example
        search_keyword = "example"
        search_results = generator.search_documentation(search_keyword)
        print(f"Search results for '{search_keyword}':")
        for name, docstring in search_results.items():
        print(f"Name: {name}")
        print(f"Documentation: {docstring}\n")

    # Customizable template example
        template_path = "template.html"
        output_path = "customized_documentation.html"
        generator.generate_customized_html(template_path, output_path)
        print(f"Customized HTML documentation generated at '{output_path}'")

# Contribution 

We welcome contributions from the community to help improve PyDocX and make it even better! Whether you're fixing a bug, adding a new feature, or improving documentation, your contributions are appreciated.

# How To Contribute

1) Fork the Repository: Start by forking the PyDocX repository to your own GitHub account.
2) Clone the Repository: Clone your forked repository to your local machine using the following command:
  git clone https://github.com/your-username/PyDocX.git
3) Create a Branch: Create a new branch for your contribution: 
  git checkout -b feature/your-feature-name
4) Make Changes: Make your desired changes to the codebase. Ensure that your changes follow the project's coding conventions and style guidelines.
5) Write Tests: If applicable, write tests to cover your changes and ensure that they work as expected.
6) Commit Changes: Once you've made your changes, commit them with a descriptive commit message:
  git commit -am 'Add new feature: your-feature-name'
7) Push Changes: Push your changes to your forked repository:
  git push origin feature/your-feature-name
8) Submit a Pull Request: Finally, submit a pull request from your branch to the main PyDocX repository. Be sure to provide a detailed description of your changes and any relevant information.

# License
PyDocX library has been licensed under CC BY 4.0, which means if someone is remixing or commercially using this library they will have to include a credit to the actual creator for their contribution to this project.
