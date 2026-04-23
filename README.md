<img width="925" height="794" alt="image" src="https://github.com/user-attachments/assets/967d8a6f-2e36-4bf2-ac0d-f6a119483332" />
<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/ee2780ec-0325-4a76-9564-d7dc379d852a" />

<img width="1529" height="820" alt="image" src="https://github.com/user-attachments/assets/916a306b-1d92-448c-a693-c7c134a330fa" />


document.addEventListener("paste", function(e){
    e.stopImmediatePropagation();
}, true);

document.addEventListener("keydown", function(e){
    if(e.ctrlKey && e.key.toLowerCase() === "v"){
        e.stopImmediatePropagation();
    }
}, true);
