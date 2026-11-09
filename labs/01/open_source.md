# VS Code by Microsoft

The 'project' I chose is VS Code. It's an interactive development environment made by Microsoft. <br>
It's leightweight due to its heavily webbased core. It can be customized like a 'swiss pocket knife' with extensions, available in a native  marketplace. 

## 1. what license regulates VS Code? 

> [!NOTE]
> Short answer: MIT License

The MIT license is of permissive nature and let's you copy an re-use the code it holds. It does not require that you MUST re-use the license in <br>
everything you do. Though it is highly suggested that you do  when publishing substantial amounts or the eniterity of the code it orgianlly was applied to.

## 2. What do machines see? 
The goal is the see what machines register as a license and where they have to look for that. <br>
In this case it's in the JSON code of the API, Underneath the spdx_id tag. <br>

**let's have a look**
In my personal project called _pinotiq_ there is no license so apparently no `spdx_id` tag either. \
in my data-integration repo there should be one. Let's see in the API. YES. spdx_id: "MIT"  \

in the _our world in data_ CO2 repo holds a license section in the README but not a separate license listed in the Repo. The API doesn't catch this <br>
hence, there is no spdx_id in the AP I 

## 3. Community files
Community files. Which of README, LICENSE, CONTRIBUTING and CODE_OF_CONDUCT does the project have? \
the vs code repo has al; of them.

## 4. Contributers to VS code: 
In total there are 2.624 contributors to this day (9.11.2026). \
unfortunately i cannot see who has the rights to merge. 

## 5. Money
Microsoft is funding VS code. \
I cannot find a "Sponsor Us" button

## 6. Activity
The last release was 3 days ago. So far, there are still 18,618 issues open. Open pull requests sit at 3146 at the moment

## 7. My Way in. 
the VS Code repo holds a very detailed contributing md file which tells me exactly how to report an issued.  \
can be found [here](https://github.com/microsoft/vscode/blob/main/CONTRIBUTING.md#Writing-Good-Bug-Reports-and-Feature-Requests)
There is a Wiki [here](https://github.com/microsoft/vscode/wiki/How-to-Contribute) that shares some more technical specifications needed to submit an issue. \
There is indeed also a list of 'good first issues'. 






