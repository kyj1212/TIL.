1레벨 이상한 문자

function solution(s) {
    var answer = '';
    for(let i=0; i<s.length; i++){
        if(i%2==0){
            answer+=s[i].toUpperCase()
        }else{
            answer+=s[i].toLowerCase()
        }
    }
    return answer;
} 


코드를 짜긴했지만 일정 부분만 해당이되고 몇개는 실행이 안되는거같다,,,
왜 다 부합이 안되는지는 내일 확인해봐야겠다

let s = 'korea usa china'
function solution(s){
    let x = s.split()
    let answer = []

    for(let i=0; i<x.length; i++){
        answer.push(x[i].split('').map((a,b) => b%2===0)
    }
}

function solution(n){
    let answer= 0;
    let m = n.toString()  // split을위해 문자로 바꿔준다
    let k = m.split('')

    for(let i=0; i<k.length; i++){
        answer = answer + Number(k[i])
    }
    return answer
} 이상한 문자 만들기 알고리즘

function solution(seoul){
    let answer = ''
    for(let i=0; i< seoul.length; i++){
        if(seoul[i]==='kim'){
            answer = '김서방은 'i'에 있다'
        }
    }
    return answer
} 서울에서 김서방 찾기 // 내가 푼 알고리즘

function solution(seoul){
    for(let i=0; i< seoul.length; i++){
        return 김서방은 i에 있다
    }
} // 다른 사람이 푼 알고리즘 훨씬 간단하다