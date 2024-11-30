# CV

## Satenik Yeghoyan

**E-mail:** satisatinka@icloud.com  
**GitHub:** [github.com/SatiYeghoyan](https://github.com/SatiYeghoyan)  
**Tel:** 797-000-000  
**Date of birth:** 24.07.0000  
**City:** Warsaw  

---

## Summary

**Junior Programmer** skilled in HTML, CSS, JavaScript, and TypeScript. I am highly motivated to contribute to a collaborative team while continually developing my coding skills. My goal is to bring creativity and a solutions-driven mindset to a dynamic development environment where I can learn from experienced developers and actively contribute to impactful projects.

---

## Skills

- **Languages:** JavaScript, TypeScript  
- **Web Development:** HTML, CSS, Node.js  
- **Version Control:** Git, GitHub  
- **Other Tools:** Visual Studio Code

---

## Code Examples

```javascript
async function getApi() {
    const response = await fetch("https://www.cbr-xml-daily.ru/daily_json.js");
    const data = await response.json();
    console.log(data);
    getThead(data);
    convertValue(data);
}
