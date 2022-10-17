const bar= document.querySelector('#bar')
const close= document.querySelector('#close')
const nav= document.querySelector('#navbar')

if (bar) {
    bar.addEventListener('mouseover', ()=>{
        nav.classList.add('active')
    })

    
}
if (close) {
    close.addEventListener('click', ()=>{
        nav.classList.remove('active')
    })
    
}
// if (nav) {
//     nav.addEventListener('mouseout', ()=>{
//         nav.classList.remove('active')
//     })
    
// }

let marker= document.querySelector('.marker')
let item= document.querySelectorAll('#navbar a')

function indicator(event){
    marker.style.left = event.offsetLeft+"px";
    marker.style.width = event.offsetWidth+"px";
    }
    
    item.forEach(link => {
        link.addEventListener('click', (event)=>{
            indicator(event.target)
        })
        
    });