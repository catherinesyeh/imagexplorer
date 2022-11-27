# ImagExplorer
An AI-powered brainstorming tool for writer-artist collaboration

Made with:
* Stable Diffusion ([Replicate API](https://replicate.com/stability-ai/stable-diffusion/api))
* Flask

## setup instructions
1. clone repo
```
git clone https://github.com/catherinesyeh/imagexplorer.git 
```

2. create virtual env
```
python3 -m venv env
```

3. activate env
```
source env/bin/activate
```

4. install requirements
```
pip3 install -r requirements.txt
```

5. set replicate API token env variable (grab token [here](https://replicate.com/account))
```
export REPLICATE_API_TOKEN=[your API key]
```

6. start app
```
python3 app.py
```
