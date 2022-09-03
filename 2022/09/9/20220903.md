react를 이용하면 되게 편안한다
1.재활용성
2.가독성 등등 있다

컴퍼넌트라는게 있다 컴퍼넌트란 예시로 드는게 편안할거같다

우리가 직접 HTML을 짜면 코드가 길어질수록 가독성도 안좋아지고 힘들다 그럴떄 사용하는게 컴퍼넌트인데
class abc extends compoent{
    render(){
        return{
            이 사이에 html을 넣어주면 된다
        }
    }
}


밑부분에 보면

class app extends compoent{
    render(){
        return{
            
        }
    }
} 이런 게 있을것이다

class app extends compoent{
    render(){
        return{
            <abc></abc>
        }
    }
}
이사이에 이런식으로 넣어주고 실행해보면 코드 내용이 나올 것이다

오늘 공부해본 것은 react설치과정,react코딩,react파일 구조 등등을 대충 알아보았다
아직은 익숙하지 않지만 잘 쓰면 매우 활용성이 좋을 거 같다 

아 그리고 css도 넣는것도 배웠닷 -끝- 




props란

class abc extends compoent{
    render(){
        return{
            {props.name.gom}
        }
    }
}

class app extends compoent{
    render(){
        return{
            p
        }
    }
}
