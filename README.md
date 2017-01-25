## Login from external pages

This repository provides a small example for our customers in order to provide login functionality to Företagsplatsen
on their own websites.

In case of any problems, please contact our support via [support@foretagsplatsen.se](mailto:support@foretagsplatsen.se)

### (1) Link to our login page

If you don't want to provide customized login functionality on your page and want to solely rely on our login pages; please
link to [web.foretagsplasten.se](https://web.foretagsplatsen.se).

### (2) Put a form on your website

If you want to put a customized login form on your website, `example-login.html` provides a minimal example to display 
a login form for Företagsplatsen.

## Tips

- Use `https` only

- If your using (1) or (2) in a frame please set TARGET="_top". E.g.

    For (1)
    ```
    <a href="..." target="_top">
    ```
    For (2)
    ```
    <form … target="_top">
    ```

