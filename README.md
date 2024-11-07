COLAB: https://colab.research.google.com/drive/17244HTk2r_wexGAdwUo8q5_mocuu_VUH?usp=sharing


PIPPA: 
colab + python + dataset pippa_deduped.jsonl (
the pippa_deduped.jsonl contains 16k+ objects like this:
{
    "submission_timestamp": "integer (timestamp in milliseconds)",
    "categories": "array or null",
    "bot_id": "string",
    "bot_name": "string",
    "bot_greeting": "string",
    "bot_definitions": "string",
    "bot_description": "string",
    "conversation": [
        {
            "message": "string",
            "is_human": "boolean"
        }
    ]
}
) 

the model i want to use (https://huggingface.co/meta-llama/Llama-3.2-1B)

I want to create a new fine tuned version of meta-llama/Llama-3.2-1B model using the previous dataset.