function Desenvolvedor() {}

// SobreMim.js
class SobreMim extends Desenvolvedor {
  constructor() {
    super();
    this.nome = 'Diógenes da Silva Pasqualoto';
    this.area = 'TI';
    this.trabalho = 'for now looking...';
    this.local = 'RS';
  }
}

// Skills.js
class Skills extends Desenvolvedor {
  constructor() {
    super();
    this.frontEnd = {
      linguagens: ['HTML', 'CSS', 'JavaScript'],
      frameworks: ['Vue.js'],
      bibliotecas: ['jQuery', 'Bootstrap'],
      ferramentas: ['Webpack', 'Gulp']
    };

    this.backEnd = {
      linguagens: ['JavaScript', 'Java', 'PHP'],
      frameworks: ['Node.js', 'Express'],
      bancosDeDados: ['MySQL', 'MongoDB', 'PostgreSQL']
    };

    this.outrasHabilidades = ['Git', 'Linux'];

    this.metodologias = ['Scrum', 'Kanban'];
  }
}

// Exemplo:
const sobreMim = new SobreMim();
console.log(sobreMim);

const skills = new Skills();
console.log(skills);
