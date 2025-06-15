# zaqathon
Upload of my Zaqathon solutions.

The problem was as follows:
The Challenge:
This system takes in as input raw emails from customers (forwarded, messy, or multi-threaded) and
automatically:
1. Extracts the purchase request from emails received (connected to email). Identify SKUs (products)
requested, quantities, and delivery requirements from unstructured email content.
2. Validates the request. Check against the provided product catalog for:
SKU existence
MOQ (Minimum Order Quantity)
Inventory availability
3. Output a JSON with validated SKUs, quantity, customer notes, and delivery preference
4. Flags any issues. If something is wrong and proposes solutions (e.g. SKU doesn’t exist, minimum
order quantity not met, suggests lumping orders together to meet quantity requirements, suggest a
valid replacement)
5. Bonus:
User interface to approve/edit replacements
Confidence scores per extracted field
Reusable code modules (clean architecture)
Operator/BrowserUse agent that takes the JSON file and fills sales order form PDF

Requirements:
Inputs are linked from the email service directly
SKU (product) catalog (shared)
Output: JSON object of clean order data + basic UI for human review experience

You Will Be Provided:
A mock product catalog (catalog.csv) with SKUs, descriptions, MOQ, price, stock and more
5 sample emails in raw .txt form with messy formatting and conversation threads

What We’re Evaluating:
Your approach to dealing with messy inputs
The correctness and UX of the structured output
Creativity in fallback or substitution logic
Speed and scrappiness of implementation





I immediately recognized that 1.5 hours of actual coding was not enough time to solve these problems successfully, so alternatively, I first came up with a plan as to how to complete each problem and the format by which to complete it, then I used LLM's to assist me with the raw coding. This maximized the efficiency of the task and was the only way that would have allowed me to complete most aspects. Given more time, I would have likely significantly reduced the use of AI to assist with the code, as it can be messy and inefficient in the long term. Thank you again!
