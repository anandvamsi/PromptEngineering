# Long Article
- Imagine a case where you have a long article, you want to answer the article.
Split the article in multiple parts and find parts where question is answered by using a ```similarity search```

- split the articles in multiple chucks using ```RecursiveCharaterTextSplitter```
- Do the similarity search of question with each chuck using ```Facebook AI algo FAISS```
