## Links

- **GitHub repo:** https://github.com/faynasser/movie-picture-pipeline

- **Frontend URL (ELB):**  
  http://ad748560997304bcc9c501eaa66236fa-646151782.us-east-1.elb.amazonaws.com/

- **Backend URL (ELB):**  
  http://ace12022be914474b96521a1a76a7280-1267166387.us-east-1.elb.amazonaws.com/movies

### Verification

- Visiting the **frontend** shows the **Movie List** and **Movie Details**.
- Visiting the **backend** `/movies` endpoint returns JSON.

```bash
# Backend JSON
curl http://ace12022be914474b96521a1a76a7280-1267166387.us-east-1.elb.amazonaws.com/movies

