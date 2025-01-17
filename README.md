# AI-patent-summary - OpenAI and Gemini

This tool provides a well-written summary for patent using AI. To write the summary we take patent number as input and extract the title, claim and full text from Google Patents. 

Then we pass on the patent details with specialized prompts to **OpenAI and Gemini using their API**. The first paragraph summarizes the first claim and picks the scope from patent description. The second paragraph provides a summary of problem being solved by the patent and the advantages of the patent.

The results are presented on a clean UI made using **Gradio**.
