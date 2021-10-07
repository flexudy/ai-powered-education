# ai-powered-education

[Flexudy](https://flexudy.com "Flexudy") is an AI-powered open source solution for end-to-end automated content
generation in the field of education. Our mission is democratise education across the globe. Try our
hosted [web application here](https://app.flexudy.com "Web App")

[<img src="flexudy-avatar.png" width="50" align="left"/>](Flexudy-Avatar)
</br></br>

## OMQD (Open Multi-lingual Question Answering Dataset)

1. OMQD is a new challenging question answering dataset.
2. OMQD is multi-lingual (3632 German samples, 2322 English samples).
3. OMQD was created by humans for machines.
4. OMQD is based on didactic taxonomy levels. Some question operators include: *"describe", "name", "identify", "explain"*.
5. OMQD passages were extracted from several sources across the web.
6. OMQD was developed with the support of the **Friedrich-Alexander University of Erlangen-Nuremberg**, **RWTH Achen University** and the **Karlsruhe Institute of Technology**.

### Example

```python
question = "Name the disease that is associated with epidermolysis bullosa simplex with late-onset muscular dystrophy."

context = """A compound heterozygous one amino-acid insertion/nonsense mutation in the plectin gene causes 
epidermolysis bullosa simplex with plectin deficiency. Plectin is a cytoskeleton linker protein expressed 
in a variety of tissues including skin, muscle, and nerves. Mutations in its gene are associated with epidermolysis 
bullosa simplex with late-onset muscular dystrophy."""

answered = False  # This question is not answerable

answer = "" # If answered is True, this is not empty.
```

Link to dataset: [OMQD](https://huggingface.co/datasets/flexudy/OMQD "OMQD")

### Test Set
We have a secret test set of over 1000 questions. We will maintain a [Leaderboard here](https://github.com/flexudy/ai-powered-education "OMQD Leaderboard").
So, zip, upload and send us the location your model and execution script for evaluation.

e.g `your-name-or-team-name.zip`

Here is how the interface should look:

```python
def predict_answer(context: str, question: str) -> str:
    pass
```

Flexudy will not participate for fairness reasons.

## Citation and Authors

Should you find this repository helpful, please give us a star ⭐ and mention us in your publication:

```json
{
  "title": "AI-Powered Education",
  "author": "Flexudy Education",
  "url": "https://flexudy.com",
  "year": 2021
}
```

Send us an email at info@flexudy.com if you have any questions or just want to send us feedback.

