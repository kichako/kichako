# ¡Hola! ¡Soy Edward Umaña! 👋

¡Hola! Soy un desarrollador Front-end con 3 años de experiencia trabajando con WordPress y ReactJS/NextJS. Me encanta crear soluciones innovadoras para problemas complejos y siempre me mantengo actualizado en las últimas tendencias y tecnologías de mi campo. Además, me apasiona el mundo de los videojuegos, el anime y explorar la naturaleza. ¡Bienvenido!

```javascript
const MySkills = () => {
    const skills = [
        "HTML",
        "CSS",
        "JavaScript",
        "PHP",
        "WordPress",
        "ReactJS",
        "NextJS",
        "Gatsby",
        "SASS",
        "Figma",
        "TypeScript"
    ];

    return (
        <div>
            <h2>Mis habilidades y tecnologías:</h2>
            <ul>
                {skills.map((skill, index) => (
                <li key={index}>{skill}</li>
                ))}
            </ul>
        </div>
    );
}
 
export default MySkills;
```
