# AI Robot Position Finder
[PyPI Page](https://pypi.org/project/ai-robot-position-finder)

![alt text](/images/image.png?raw=true)

## Installation

```bash
pip install ai-robot-position-finder
```


**First Time Only**
This app requires a config.json file present in the working directory 
*Which should contain the following*
```json
{
    "initial_position_url": "https://github.com/AI-Robot-GCEK/robo-initial-positions/blob/main/src/initial-positions.h",
    "servo_count": 16,
    "control_api": "setServo",
    "ip": ""
}
```
> Some Thisgs to note
> - i have provided the initial_positions as a url , and it is `scraped` using a module called `ai-robot-position-scraper` you can find it [here](https://pypi.org/project/ai-robot-position-scraper/) , If you want to change that and want to do something like , provide a list inside the json or something create a issue or update the app and send a pr. 

## Usage

```
ai-ps
```
