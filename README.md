### Hi there 👋

<!--
**ChoYeSeul/ChoYeSeul** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

``` javascript
  <MyInfoTopWrap>
                <MyInfoImgBox>
                    {/* 사진파일은 10MB 미만의 JPG, PNG */}
                    <MyInfoImgWrap>
                        <MyInfoImg src={ userInfo.user_profile ? imgURL + userInfo.user_profile : ProFileIcon} alt="기본이미지"/>
                    </MyInfoImgWrap>
                    {   EditPage  ?
                            <MyInfoImgText onClick={() => {setProFilePop(true);body.style.overflow = 'auto';}}>프로필 등록</MyInfoImgText>
                        :
                        null
                    }
                </MyInfoImgBox>
                <MyInfoTextBox>
                    <MyInfoTitle>
                        <UserName>{value}님</UserName>의 회원정보 입니다.
                    </MyInfoTitle>
                    <PC>
                        <MyInfoDesc>오른쪽 ‘회원정보 수정’을 통해 회원정보를 수정할 수 있습니다.</MyInfoDesc>
                    </PC>
                    <Mobile>
                        <MyInfoDesc>오른쪽 상단 ‘회원정보 수정’을 통해 회원정보를<br/> 수정할 수 있습니다.</MyInfoDesc>
                    </Mobile>
                </MyInfoTextBox>
                <EditBtnWrap onClick={onClick}>
                    <p>회원정보 수정</p><img src={EditIcon} alt="수정 아이콘"/>
                </EditBtnWrap>
            </MyInfoTopWrap>
```
