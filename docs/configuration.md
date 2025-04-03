# Configuring PyCharm for COMP1510

This document will cover correctly configuring the IDE for COMP1510. Namely, ensuring that PEP-8 formatting is checked, and adding a GitHub token to enable you to submit code for lab assignments. The steps here will be the same regardless of your operating system. COMP1510 requires PyCharm to be configured in a certain way in order to make the most use of it in lab assignments, and one of the easiest ways to avoid losing marks is to ensure that it is configured properly.

## Opening PyCharm Settings

Do this first, as the next two sections will assume you have already done this.

1. Open PyCharm and click `Customize` from the landing screen.
![](img/configuration/landing-screen.png)
Then click `All settings...`
![](img/configuration/landing-screen-configuration.png)


2. If you have previously opened a PyCharm project, PyCharm will re-open that project when it launches and will not show the landing screen. In this case, click the gear icon in the window header, and then click `Settings...` from the dropdown.
![](img/configuration/project-configuration.png)

3. In both cases, this settings panel should appear:
![](img/configuration/settings.png)

<!-- I can't get screenshots for this because my student license is already activated and I can't activate it a second time. -->
<!-- ## Activating Your Student License

You have 30 days from when you install PyCharm Professional to activate your license. If you attend BCIT or another university or college, you likely already have free access to the premium versions of most Intellij products, including PyCharm. Otherwise, you will have to pay for PyCharm Professional, or you can switch to the free PyCharm Community version which does not require activation.

PyCharm Community lacks some of the more advanced features of PyCharm Professional, but it is still a full-fledged, powerful IDE and is perfectly usable for most software development applications. Most of the steps in this guide are identical in both PyCharm Professional and Community. -->

## Configuring PEP-8 Validation 

PEP-8 is a standard in Python that specifies how code should be formatted. COMP1510 strictly enforces PEP-8 formatting, and any deviation will result in lost marks. Therefore, it is important to ensure that the IDE is configured to check for PEP-8 and warn you when code does not conform to it.

1. In the settings panel, type `pep 8` into the search bar.

2. Click on the `Profile` dropdown, and select `Default IDE`. This ensures that the settings are applied to the entire IDE and is used as the default for all new projects; instead of being applied to only the currently open project.

3. There should only be two visible settings: `PEP 8 coding style violation`, and `PEP 8 naming convention violation`. Ensure both are checked. They may already be checked by default, but if not, check them.
![](img/configuration/pep8-search.png)

4. Click on `PEP 8 coding style violation`, and set the **Scope** to `In All Scopes`, set the **Severity** to `Warning`, and set the **Highlighting in editor** to `Warning`. 
![](img/configuration/pep8-setting1.png)

5. Click on `PEP 8 naming convention violation` and set the same three parameters as specified in the previous step. This step and the previous step will result in a yellow line under any code that does not conform to PEP-8 formatting. When programming, you can hover your mouse over the yellow line to see the specific PEP-8 rule that the code does not conform to, allowing you to fix it.
![](img/configuration/pep8-setting2.png)

6. Click `Apply` to save the changes.
![](img/configuration/pep8-apply.png)
