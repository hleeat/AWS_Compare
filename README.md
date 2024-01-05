# AWS_Compare
<div style="text-align: left;">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🧑‍💻 Compare Performance among Instance Types </h2>
    <div style="text-align: left;"> 
        <img src='./images/compare_by_chart.png'>
        <img src='./images/image_of_compare.png'>
    </div>
    <div style="font-weight: 700; font-size: 15px; text-align: left; color: #282d33;"> 그래프와 표를 통해 각 인스턴스 유형에 따른 실행 시간과 CPU 사용률을 비교하고 연관성을 확인할 수 있습니다. 그래프에서 몇 가지 관찰 사항은 다음과 같습니다:<br/><br/>
    실행 시간: t2.large (x86) 인스턴스가 가장 짧은 실행 시간을 보여주어 작업 처리가 가장 빠른 것으로 나타납니다. 반면에 m5a.large (x86)는 가장 긴 실행 시간을 보여주어 상대적으로 작업 처리 속도가 가장 느린 것으로 보입니다.<br/><br/>
    CPU 사용률: t2.large (x86) 인스턴스는 높은 CPU 사용률(11.1%)과 낮은 실행 시간을 보여주어, CPU 자원을 효과적으로 활용하여 작업을 빠르게 처리하는 것으로 해석할 수 있습니다. 다른 ARM 기반 인스턴스들은 CPU 사용률이 상대적으로 낮으며, 특히 t4g.small (arm)과 m5a.large (x86)은 0.25%의 매우 낮은 CPU 사용률을 보여줍니다.<br/><br/>
    아키텍처 차이: ARM 기반의 t4g 시리즈는 일관되게 낮은 CPU 사용률을 보이는 반면, t2.large (x86)와 같은 x86 기반 인스턴스는 더 높은 CPU 사용률을 보입니다. 이는 아키텍처에 따른 성능 차이를 반영할 수 있으며, ARM 인스턴스가 더 효율적인 전력 사용을 보여줄 수 있음을 시사합니다.<br/><br/>
    비용 대 성능: ARM 인스턴스는 일반적으로 비용 효율성이 높다고 알려져 있습니다. 이 그래프는 비용과 성능 사이의 균형을 찾는데 도움이 될 수 있습니다. 예를 들어, t2.large (x86)가 비교적 높은 성능을 보여주지만 CPU 사용률도 높은 반면, ARM 기반 인스턴스는 낮은 성능에도 불구하고 매우 낮은 CPU 사용률을 보여 비용 효율적일 수 있습니다.<br/><br/>
    이러한 관찰은 각 인스턴스 유형의 성능 및 비용 효율성을 평가할 때 유용할 수 있습니다. 그러나 이러한 결론을 내리기 위해서는 추가적인 정보가 필요합니다. 예를 들어, 각 인스턴스 유형의 시간당 비용, 워크로드의 성격, 메모리 사용량 및 네트워크 대역폭과 같은 다른 리소스의 사용량을 고려해야 할 수 있습니다. <br/><br/>​ 
    </div>
</div>