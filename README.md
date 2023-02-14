const jedi = [];
console.log(jedi);

jedi = [`Luke`];

const pushJedi = jedi.push(`Obi-Wan Kenobi`);

const unshiftJedi = jedi.unshift(`Yoda`);

console.log(jedi[0]);

const pushJedi = jedi.pop();
console.log(jedi); 
console.log(pushJedi);

const unshiftJedi = jedi.shift();
console.log(jedi); 
console.log(unshiftJedi); 

const Villains = [
const sithLords = [
  `Darth Vader`,
  `Darth Sidious`,
  `Darth Maul`
]

const imperialOfficers = [
    `Grand Moff Tarkin`,
    `Orson Krennic`
]
];

const starWarsVillains = Villains.concat(sithLords, imperialOfficers);
console.log(starWarsVillains);

starWarsVillains = `Darth Maul`.slice(0, 3);
console.log(starWarsVillains);

const droids = {
 astromech: "R2-D2"
 protocol: "C-3P0"
 assassin: "IG-88"
};
console.log(droids[`astromech`]);
console.log(droids.protocol);
droids[`assassin`] = `IG-11`;
console.log(droids[`assassin`]);  
