# 3rd-ReactApp
import logo from './logo.svg';
import './App.css';

function App() {
  return (
    <div className="App">
      import logo from './logo.svg';
import './App.css';

function App() {
    let details=[['Jack','Masha',24,'Apel']['Khutso','Monoge', 22, 'Atok']]
  return (
    <div className="App">
        let name=[]
        let surname=[]
        let gender=[]
        let age=[]

        for (let i=0;i<5;i++)
        {
            let name = prompt('Enter your name','');
            let surname= prompt('Enter surname','');
            let location= prompt('Enter location','');
            let age= prompt('Enter age','');
            for(let p=0;p<5;p++)
            {        
                console.log(name[i][p]+ " | " + surname[i][p] + " and " + age[i][p] + checkAge);
            }
        }
        console.log("name|surname|gender|age");
        


        function checkAge()
        {
            let comdition = []
            if (age>=18)
            {
                condition = "you are old enough to code";
            }
            else
            {
                condition ="you are old enough to code";
            }

            console.log(condition);
        }
        checkAge();

    </div>
  );
}
export default App;
