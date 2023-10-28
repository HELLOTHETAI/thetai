## de-duplication
In this Module, We use a very simple way to do this operation. Refer to below field.
- Article title
- date
If there is the same title and date between two articles, we judge they are the same article.

```python
if (title + date).hascode in the database:
    discard this text
else:
    insert it  
```