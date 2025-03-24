# Zoocha Call To Action Paragraph Installation Guide

To install the Zoocha Call To Action Paragraph, follow the steps below:

1. Open your terminal.
2. Navigate to your project directory.
3. Add the below in the Drupal Root's composer.json installer-paths
    ```sh
    "web/recipes/custom/{$name}": ["type:drupal-recipe"]
    ```
4. Run the following command to execute the Zoocha Call To Action Paragraph installation:

    ```sh
    ddev drush recipe recipes/custom/zr-para-cta
    ```

This command will execute the Zoocha Call To Action Paragraph installation.
