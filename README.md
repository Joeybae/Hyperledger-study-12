# Hyperledger-study-12

하이퍼레져 앱 만들기 실습 12일차 - 문자 출력 및 배포

1. 앱 설치 및 실행

        # create-react-app .
        # npm run start

2. App.js 내용 수정

        class App extends Component {
          render() {
            return (
              <div className="App">

              </div>
            );
          }  
        }

        export default App;

3. Hello, react!! 출력 - App.js 내용 수정

        class App extends Component {
          render() {
            return (
              <div className="App">
                Hello, react!!
              </div>
            );
            }  
        }

        export default App;

4. 배포하는 법

        # npm run build

5. 주소 생성

        # npx serve -s build


