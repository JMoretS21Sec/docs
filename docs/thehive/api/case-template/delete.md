# Delete

Delete a *Case Templates*.

## Query

```plain
DELETE /api/case/template/{id}
```

With:

- `id`: *Case template* identifier


##  Response 

### Status codes

- `200`: if Case Template is deleted successfully
- `401`: Authentication error
- `403`: Authorization error