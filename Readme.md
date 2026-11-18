This repository contains the data-collection and annotation artifacts for our study of scams affecting older adults on Reddit and Baidu Tieba. For each platform (reddit and tieba), the files follow three parts of the workflow: keyword retrieval and filtering, the post or thread IDs retained in the screened corpus, and the codebooks and prompts used for labeling. Raw post text and source-post examples are not included.

- `reddit_keywords.txt`: Keywords for retrieving and filtering Reddit posts.
- `reddit_post_ids.csv`: Reddit post IDs.
- `reddit_prompt.txt`: Reddit labeling prompt, codebook, and output format.
- `tieba_keywords.txt`: Keywords and filtering rules for Tieba threads.
- `tieba_prompt.txt`: Tieba labeling instructions and production/analysis codebooks.
- `tieba_thread_ids.csv`: Baidu Tieba thread IDs.

To open a Tieba thread, append an ID from the `thread_id` column to `https://tieba.baidu.com/p/`, e.g., https://tieba.baidu.com/p/232943920.
