# Javascript-Limit-Characters

#### Key points in the project:

**body linear gradient**
background: linear-gradient(to top, #81eee5 0%, #10add8 100%);

**input transition**
transition: all 0.1s ease;

**onkeyup**
input.onkeyup = () => {
    counter.innerText = maxLength - input.value.length;
}

**input maxlength attribute**
maxlength="16"
