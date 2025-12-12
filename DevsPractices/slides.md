# Being a boyscout

---

## Philosophy

Leave the code better than you found it

---

## Purpose
- Reduce technical debt<br>
- Improves Team Collaboration<br>
  - Code belongs to the team not to individuals<br>
- Reduce cost of large refactoring<br>
- Improve readability
- Builds Long-Term Habits

---

## Pre-requisite
- Requires good Git discipline<br>
- Need a shared vision between team members<br>
  - It is not about personal preferences !
- Improve the use of PR<br>

---

## How to apply the boy scout rule
- Rename unclear variable<br>
- Remove dead code<br>
- Simplify conditionals <br>
- Tests
- Fix comments

---

## Rename unclear variable
<!-- .slide: style="text-align: left;"> -->
<pre><code data-line-numbers="1-2|4-5">// Before
int x = 5;

// After
int numberOfItems = 5;
</pre></code>

---

## Remove dead code
<!-- .slide: style="text-align: left;"> -->
<pre><code data-line-numbers="1-4">// TODO : To delete
// randomFunkyMethod();
// randomFunkyMethod2();
// Not sure if it works, keeping it in case of rollback
</pre></code>


---

## Simplify conditionals
<!-- .slide: style="text-align: left;"> -->
<pre><code data-line-numbers="1-8|9-18">// Before
public void processOrder() {
    // Complex part to handle stock
    if (stock >= orderQuantity) {
        // Handle query
    }
}

// After - Refactoring by method extraction
public void processOrder() {
    if (isStockSufficient()) {
        // Handle query
    }
}

private boolean isStockSufficient() {
    return stock >= orderQuantity;
}
</pre></code>

---

## Tests

You can't refactor without tests.

---

## Fix comments
<!-- .slide: style="text-align: left;"> -->
<pre><code data-line-numbers="1-3|5-7">// Before
// Compute item price with VAT
computeWithoutVAT();

// After
// Compute item price without VAT
computeWithoutVAT();
</pre></code>

---


## Traps to avoid as a boy scout

- Sunk cost fallacy => Know when to stop
- Large refactoring still require a separate task with a separate time slot<br>
- Lack of sharing

---

