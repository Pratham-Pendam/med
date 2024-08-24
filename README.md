# End-to-end-Medical-Chatbot-using-Llama2

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mchatbot python=3.8 -y
```

```bash
conda activate mchatbot
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


### Download the quantize model from the link provided in model folder & keep the model in the model directory:

```ini
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```

```bash
# run the following command
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- Meta Llama2
- Pinecone
- 
 ###Demo
![095e7b6c4ef55a755031536c26d227106ba2929e](https://github.com/user-attachments/assets/cdac7d2e-8278-4560-bb9b-cdc84ceadd6d)


![WhatsApp Image 2024-08-24 at 20 06 00_54a58681](https://github.com/user-attachments/assets/9416ad74-9787-4e4e-89f0-51af0e5536aa)

![a2602d607286addc3a9250a5f2fc62a70a2e0cdb](https://github.com/user-attachments/assets/9ccc7024-6be5-491d-9881-37a7d4aae835)

###Demo![1d35ab470aadf492c3a3aad7ca91f5777ce00270](https://github.com/user-attachments/assets/636447d5-80cc-4a49-846e-3d78d1108644)
![WhatsApp Image 2024-08-24 at 20 06 02_99251f35](https://github.com/user-attachments/assets/4a2479b7-90dd-4f4c-9466-ffbd8ee9e061)
![WhatsApp Image 2024-08-24 at 20 06 02_5c8c3b5e](https://github.com/user-attachments/assets/9fda54e0-2af0-4437-b804-0d41cf4c458b)

![WhatsApp Image 2024-08-24 at 20 06 01_8d8190cc](https://github.com/user-attachments/assets/f5ca232f-1b60-4d75-b969-0eaf0eb1ab9a)

![6e02a94fcdd68549ebac3e7ebc3c54e6f6d3c932](https://github.com/user-attachments/assets/3749a2e5-2bff-417a-bb29-1c84f6c411a1)
