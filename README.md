# study_of_behave

This repository aims to understand how to handle behave as python-it.<br>
Please check [behave Examples and Tutorials](https://jenisys.github.io/behave.example/index.html) if you want to know more detail.

## Tutorials
- Tutorial 1: First Steps
- Tutorial 2: Natural Language
- Tutorial 3: Step Parameters
- Tutorial 4: Scenario Outline
- Tutorial 5: Multi-line Text (Step Data)
- Tutorial 6: Setup Table
- Tutorial 7: Result Table
- Tutorial 8: Execute Other Steps in a Step
- Tutorial 9: Use Background
- Tutorial 10: User-defined Data Type
- Tutorial 11: Use Tags
- Tutorial 12: Use another Spoken Language

## How to run

First of all, you need to prepare behave environment.<br>
And then, you can execute following Tutorials.

    $ pip install -r requirements.txt
    $ cd steps

<u><h4>Tutorial 1</h4></u>

    behave ../features/tutorial01_basics.feature

<u><h4>Tutorial 2</h4></u>

    behave ../features/tutorial02_natural_language.feature

<u><h4>Tutorial 3</h4></u>

    behave ../features/tutorial03_step_parameters.feature

<u><h4>Tutorial 4</h4></u>

    behave ../features/tutorial04_scenario_outline.feature

<u><h4>Tutorial 5</h4></u>

    behave ../features/tutorial05_step_data.feature

<u><h4>Tutorial 6</h4></u>

    behave ../features/tutorial06_step_setup_table.feature

<u><h4>Tutorial 7</h4></u>

    behave ../features/tutorial07_step_result_table.feature

<u><h4>Tutorial 8</h4></u>

    behave ../features/tutorial08_step_executes_steps.feature

<u><h4>Tutorial 9</h4></u>

    behave ../features/tutorial09_background.feature

<u><h4>Tutorial 10</h4></u>

    behave ../features/tutorial10_step_usertype.feature

<u><h4>Tutorial 11</h4></u>

    $ behave --tags=-wip ../features/tutorial11_tags.feature
    $ behave --tags=ninja.chuck ../features/tutorial11_tags.feature
    $ behave --tags=-ninja.chuck ../features/tutorial11_tags.feature
    $ behave --tags=@ninja.any,@ninja.chuck ../features/tutorial11_tags.feature
    $ behave --tags=@ninja.any --tags=@ninja.chuck ../features/tutorial11_tags.feature

<u><h4>Tutorial 12</h4></u>

    $ behave ../features/tutorial12_spoken_language.feature
    $ behave --lang=de ../features/tutorial12_spoken_language.feature
