# VOL18 기획: 어깨가 가벼운 계절 | LIGHT SHOULDERS SEASON

## 앨범 콘셉트

- **분위기**: FREE TONIGHT처럼 어깨가 살짝 들썩일 정도의 가벼운 그루브. 카페에 틀어 둬도 시끄럽거나 튀지 않는다.
- **스타일**: VOL11 계열. 영어 가사이고, 20곡 중 8곡에 짧은 멜로딕 랩이 들어간다.
- **계절**: 10월에서 11월로 넘어가는 시기. 첫 입김, 목도리, 은행잎, 다섯 시 노을, 따뜻한 라떼가 나온다.
- **테마 4개 × 5곡**
  - A. 살짝 시작하려는 사랑 (1–5)
  - B. 잊었다가 문득 떠오르는 그리움 (6–10)
  - C. 다시 피어나는 사랑 (11–15)
  - D. 일상의 발견, 기쁨, 행복 (16–20)
- **훅**: 모든 곡의 후렴은 짧은 문구를 2~4번 반복하는 구조로, 한 번 들으면 따라 부를 수 있게 만들었다.

## 공통 스타일 프롬프트 (VOL18 베이스)

곡별 프롬프트에 이미 포함되어 있습니다. 새 곡을 추가할 때 이 베이스를 쓰세요.

```
laid-back autumn cafe pop, acoustic guitar, soft Rhodes piano, brushed drums, warm round bass, light head-nodding groove, maj7 and 9th chords, cozy and mellow, gentle dynamics, not loud, smooth warm mix, short 4-bar intro, catchy repetitive hook melody, clear singable chorus
```

- **보컬 태그**: 곡별로 기본값(female/male)을 적어 두었습니다. 실제로 부를 아티스트(DAYWYN/VENA/SOWYN/SERIN/ROAN)의 보컬 태그로 바꿔서 쓰세요.
- **랩 곡**: 스타일에 `soft melodic rap verse, laid-back flow`가 들어 있습니다. 랩이 너무 세게 나오면 `whispery`나 `spoken-word`를 추가하세요.

## 곡 목록

| # | 제목 | 테마 | BPM | 키 | 보컬(기본) | 랩 |
|---|---|---|---|---|---|---|
| 1 | 조금 더 가까이 \| A LITTLE CLOSER | A | 94 | D | female | |
| 2 | 네 목도리 \| YOUR SCARF ON ME | A | 90 | G | female | ● |
| 3 | 라떼 두 잔 \| TWO LATTES | A | 96 | A | male | |
| 4 | 바스락 바스락 \| CRUNCH CRUNCH | A | 100 | C | female | ● |
| 5 | 말할까 말까 \| SHOULD I SAY IT | A | 88 | F | female | |
| 6 | 문득 \| OUT OF NOWHERE | B | 84 | Bb | female | |
| 7 | 11월의 노래 \| NOVEMBER SONG | B | 82 | D | male | ● |
| 8 | 그 카페 창가 \| THE WINDOW SEAT | B | 86 | G | female | |
| 9 | 오래된 플레이리스트 \| OLD PLAYLIST | B | 90 | A | male | ● |
| 10 | 첫 입김 \| LITTLE CLOUD | B | 84 | E | female | |
| 11 | 다시, 봄처럼 \| LIKE SPRING IN NOVEMBER | C | 96 | D | female | |
| 12 | 두 번째 첫 데이트 \| SECOND FIRST DATE | C | 98 | F | male | ● |
| 13 | 은행잎 편지 \| GOLDEN LETTER | C | 92 | C | female | |
| 14 | 늦게 핀 꽃 \| LATE BLOOM | C | 90 | Bb | female | |
| 15 | 다시 너에게 \| BACK TO YOU AGAIN | C | 94 | G | male | ● |
| 16 | 다섯 시의 햇살 \| 5PM GOLD | D | 98 | D | female | |
| 17 | 좋은 하루 \| GOOD DAY, GOOD DAY | D | 100 | C | male | ● |
| 18 | 사소한 행복 \| SMALL WONDERS | D | 94 | F | female | |
| 19 | 따뜻한 오후 \| WARM AFTERNOON | D | 92 | E | male | |
| 20 | 어깨가 가벼워 \| LIGHT SHOULDERS (타이틀) | D | 100 | G | female | ● |

### 발매 분할 제안 (10곡씩 2회)

테마가 한쪽으로 몰리지 않도록 섞었습니다.

- **Part 1**: 20, 1, 6, 11, 16, 2, 7, 12, 17, 3
- **Part 2**: 4, 8, 13, 18, 5, 9, 14, 19, 10, 15

## 파일 정리 규칙

원곡과 무가사 버전을 따로 받아 따로 압축합니다. 한 압축 파일에 섞지 않습니다.

```
H:\SUNO\VOL18\
├─ 조금 더 가까이.mp3            ← 원곡 (WAV 압축 → mp3 변환)
├─ 네 목도리.mp3
├─ ...
└─ 무가사\
   ├─ 조금 더 가까이_무가사.mp3   ← Suno Cover(가사 삭제) 결과
   ├─ 네 목도리_무가사.mp3
   └─ ...
```

- 무가사 파일 이름은 **원곡 파일 이름 + `_무가사`**로 짓습니다. 원곡 파일 이름과 한 글자라도 다르면 플레이어가 짝을 찾지 못합니다.
- 윈도우 파일 이름에는 `|`를 쓸 수 없습니다. 파일 이름에는 한글 제목만 쓰고, `한글 | ENGLISH` 형식은 Suno와 유튜브 제목에만 씁니다.
- 플레이어가 지금 인식하는 무가사 경로 규칙과 맞는지 PC 로컬 세션에서 `build_meta.py`를 확인해야 합니다. 다르면 이 규칙이나 `build_meta.py` 중 하나를 맞춥니다.

---

## 곡별 가사와 스타일 프롬프트

### 1. 조금 더 가까이 | A LITTLE CLOSER

**Style**
```
laid-back autumn cafe pop, soft female vocal, acoustic guitar, soft Rhodes piano, brushed drums, warm round bass, light head-nodding groove, maj7 chords, cozy, gentle dynamics, not loud, 94 BPM, D major, short 4-bar intro, catchy repetitive hook "a little closer"
```

**Lyrics**
```
[Intro]
(mm-mm, mm-mm)

[Verse 1]
Cold wind knocking on the café door
You came in shaking off the rain
We've said hello a hundred times before
But today it doesn't feel the same

[Pre-Chorus]
Your coffee's cooling while you're talking slow
And I don't really want you to go

[Chorus]
A little closer, a little closer
Leaves are falling, so am I
A little closer, a little closer
Stay a little, stay a while
Just a step, just a step, just a little closer

[Verse 2]
You laugh at something I don't even get
And I laugh too, just to be there
Five o'clock and the sun is already set
There's an autumn kind of gold in your hair

[Pre-Chorus]
Maybe tomorrow I'll say something true
Tonight I'll just sit next to you

[Chorus]
A little closer, a little closer
Leaves are falling, so am I
A little closer, a little closer
Stay a little, stay a while
Just a step, just a step, just a little closer

[Bridge]
Not too fast, not too loud
Let it grow like a quiet sound
One more cup, one more hour
October turning into ours

[Final Chorus]
A little closer, a little closer
Leaves are falling, so am I
A little closer, a little closer
Stay a little, stay a while
Just a step, just a step, just a little closer

[Outro]
A little closer... (mm)
A little closer
[End]
```

### 2. 네 목도리 | YOUR SCARF ON ME

**Style**
```
laid-back autumn cafe pop with light R&B groove, soft female vocal, soft melodic rap verse, laid-back flow, acoustic guitar, soft Rhodes, brushed drums, warm bass, 9th chords, cozy, not loud, 90 BPM, G major, short 4-bar intro, catchy repetitive hook "your scarf on me"
```

**Lyrics**
```
[Intro]
(ooh, ooh)

[Verse 1]
First cold morning, didn't check the weather
Walking out in just a thin T-shirt
You just smiled and said "we'll share it together"
Wrapped your scarf around me, didn't say a word

[Pre-Chorus]
It smells like cedar and a little like you
Now I'm warm and I don't know what to do

[Chorus]
Your scarf on me, your scarf on me
Soft and grey like a November sea
I should give it back, but I don't wanna leave
Keep your scarf on me, your scarf on me

[Rap]
Two steps, three steps, walking in line
Your hands in your pockets, my heart out of mine
Streetlights blinking like they know what we're doing
Leaves in the gutter, the whole city's moving
I'm playing it cool but it's colder than cool
Borrowed a scarf and I'm breaking the rule
Not saying "love," not saying it yet
Just the warmest little morning I won't forget

[Pre-Chorus]
It smells like cedar and a little like you
Now I'm warm and I don't know what to do

[Chorus]
Your scarf on me, your scarf on me
Soft and grey like a November sea
I should give it back, but I don't wanna leave
Keep your scarf on me, your scarf on me

[Bridge]
Maybe I'll forget to give it back tomorrow
Maybe you'll forget to ask

[Final Chorus]
Your scarf on me, your scarf on me
Soft and grey like a November sea
I should give it back, but I don't wanna leave
Keep your scarf on me, your scarf on me

[Outro]
Your scarf on me... (mm)
Stay on me
[End]
```

### 3. 라떼 두 잔 | TWO LATTES

**Style**
```
laid-back autumn cafe pop, warm soft male vocal, acoustic guitar, soft Rhodes piano, upright-style warm bass, brushed drums, light bouncy groove, maj7 chords, cozy, not loud, 96 BPM, A major, short 4-bar intro, catchy repetitive hook "two lattes", playful "la-la-latte" backing vocals
```

**Lyrics**
```
[Intro]
(la-la-latte, la-la-latte)

[Verse 1]
Every morning, same old line
Same old barista, same old sign
But now I'm ordering one for you
Oat milk, extra hot, just like you do

[Pre-Chorus]
I don't know if you'll even come by
But I'll wait here, one more time

[Chorus]
Two lattes, two lattes on the table
One for me and one for you, maybe
Two lattes, two lattes, getting colder
Come on in before the day gets older
(la-la-latte, la-la-latte)

[Verse 2]
Rain is writing on the window glass
Little messages that never last
Then the door bell rings and there you are
Hoodie wet, cheeks red, like a falling star

[Pre-Chorus]
You look at the cups and you start to smile
"Is this one mine?" Yeah, it's been a while

[Chorus]
Two lattes, two lattes on the table
One for me and one for you, maybe
Two lattes, two lattes, getting colder
Come on in before the day gets older
(la-la-latte, la-la-latte)

[Bridge]
Maybe it's silly, maybe it's small
Maybe it's everything after all

[Final Chorus]
Two lattes, two lattes on the table
One for me and one for you, maybe
Two lattes, two lattes, getting colder
Come on in before the day gets older
(la-la-latte, la-la-latte)

[Outro]
La-la-latte...
Two lattes
[End]
```

### 4. 바스락 바스락 | CRUNCH CRUNCH

**Style**
```
laid-back autumn cafe pop, playful soft female vocal, soft melodic rap verse, laid-back flow, acoustic guitar, light ukulele accents, soft Rhodes, brushed drums with light shaker, warm bass, bouncy walking groove, cozy, not loud, 100 BPM, C major, short 4-bar intro, catchy repetitive hook "crunch crunch"
```

**Lyrics**
```
[Intro]
(crunch, crunch)

[Verse 1]
Park bench at noon, the sky is blue
Yellow leaves are falling down on you
You kick a pile and it flies so high
I haven't laughed like that in a long time

[Pre-Chorus]
Every step we take makes a little sound
Like the ground is saying "stick around"

[Chorus]
Crunch crunch, every step to you
Crunch crunch, gold and orange too
Crunch crunch, walking slow, walking slow
Crunch crunch, I don't wanna go

[Rap]
Okay, sneakers on the sidewalk, rhythm in the leaves
Laughing at the pigeons, wind up in our sleeves
You say you like autumn, I say me too
Honestly I'd like any season with you
Ginkgo on the pavement like a golden rug
Don't know what this is, might be half a crush
Walking you home, taking the long way
Crunch, crunch, that's all I'm gonna say

[Pre-Chorus]
Every step we take makes a little sound
Like the ground is saying "stick around"

[Chorus]
Crunch crunch, every step to you
Crunch crunch, gold and orange too
Crunch crunch, walking slow, walking slow
Crunch crunch, I don't wanna go

[Bridge]
If the leaves all fall by November
I'll have one thing to remember

[Final Chorus]
Crunch crunch, every step to you
Crunch crunch, gold and orange too
Crunch crunch, walking slow, walking slow
Crunch crunch, I don't wanna go

[Outro]
Crunch crunch... walking slow
[End]
```

### 5. 말할까 말까 | SHOULD I SAY IT

**Style**
```
laid-back autumn cafe pop, soft breathy female vocal, fingerpicked acoustic guitar, soft Rhodes piano, brushed drums, warm bass, gentle swaying groove, maj7 chords, intimate, not loud, 88 BPM, F major, short 4-bar intro, catchy repetitive hook "should I say it"
```

**Lyrics**
```
[Intro]
(mm, maybe)

[Verse 1]
Phone in my hand at a quarter to one
Typed it all out, then deleted each one
"Hey, are you up?" No, that's not right
"Hope you slept well," it's the middle of the night

[Pre-Chorus]
Words in my chest like leaves in the wind
Don't know where they'll land, don't know where to begin

[Chorus]
Should I say it, should I say it
Maybe now, maybe not tonight
Should I say it, should I say it
Maybe you feel it, maybe you might
Oh, should I say it

[Verse 2]
Saw you today in the library light
Brown knit sweater, the sleeves pulled tight
You looked up once and you looked away
And I lost every word I planned to say

[Pre-Chorus]
Words in my chest like leaves in the wind
Don't know where they'll land, don't know where to begin

[Chorus]
Should I say it, should I say it
Maybe now, maybe not tonight
Should I say it, should I say it
Maybe you feel it, maybe you might
Oh, should I say it

[Bridge]
Maybe the season will say it for me
Maybe the cold will bring you close to me

[Final Chorus]
Should I say it, should I say it
Maybe now, maybe not tonight
Should I say it, should I say it
Maybe you feel it, maybe you might
Oh, should I say it

[Outro]
Should I say it...
(maybe tomorrow)
[End]
```

### 6. 문득 | OUT OF NOWHERE

**Style**
```
laid-back autumn cafe pop, soft wistful female vocal, acoustic guitar, soft Rhodes piano, light strings pad, brushed drums, warm bass, gentle groove, maj7 and 9th chords, bittersweet but warm, not loud, 84 BPM, Bb major, short 4-bar intro, catchy repetitive hook "out of nowhere"
```

**Lyrics**
```
[Intro]
(ooh)

[Verse 1]
Folding laundry on a Sunday
Radio playing something low
Found a ticket in my old coat
From a movie two winters ago

[Pre-Chorus]
And I didn't think I'd think of you
But here you are, out of the blue

[Chorus]
Out of nowhere, out of nowhere
You come back like the autumn air
I was fine, I didn't care
Then you're here, out of nowhere

[Verse 2]
There's a song you used to hum along
In the car when the traffic was slow
I forgot every single word
Now it's all that I know

[Pre-Chorus]
And I didn't think I'd think of you
But here you are, out of the blue

[Chorus]
Out of nowhere, out of nowhere
You come back like the autumn air
I was fine, I didn't care
Then you're here, out of nowhere

[Bridge]
It doesn't hurt, it's just a little warm
Like a light left on through the storm

[Final Chorus]
Out of nowhere, out of nowhere
You come back like the autumn air
I was fine, I didn't care
Then you're here, out of nowhere

[Outro]
Out of nowhere... (mm)
[End]
```

### 7. 11월의 노래 | NOVEMBER SONG

**Style**
```
laid-back autumn cafe pop with lo-fi R&B touch, warm soft male vocal, soft melodic rap verse, laid-back flow, acoustic guitar, dusty Rhodes, brushed drums, warm bass, mellow nodding groove, 9th chords, nostalgic but warm, not loud, 82 BPM, D major, short 4-bar intro, catchy repetitive "na-na-na" hook
```

**Lyrics**
```
[Intro]
(na-na-na, na-na-na)

[Verse 1]
Trees are almost bare on Maple Street
Coffee shop is playing something sweet
Somebody laughs like you used to laugh
And I turn around too fast

[Pre-Chorus]
It's just November playing tricks on me
Just the way it's meant to be

[Chorus]
Na-na-na, a November song
Humming it all day long
You're not here, but you're not gone
Na-na-na, a November song

[Rap]
Scrolling back to pictures from a year ago
Your hood up, cheeks red, laughing in the first snow
I don't text, I don't call, I just let it be
But the wind knows your name and it whispers to me
It's not sad, not really, it's kinda sweet
Like a song on the radio skipping a beat
So I walk a little slower, let the memory play
Then I smile and I let it drift away

[Pre-Chorus]
It's just November playing tricks on me
Just the way it's meant to be

[Chorus]
Na-na-na, a November song
Humming it all day long
You're not here, but you're not gone
Na-na-na, a November song

[Bridge]
Maybe somewhere you're humming it too
And the wind carries it back from you

[Final Chorus]
Na-na-na, a November song
Humming it all day long
You're not here, but you're not gone
Na-na-na, a November song

[Outro]
Na-na-na...
[End]
```

### 8. 그 카페 창가 | THE WINDOW SEAT

**Style**
```
laid-back autumn cafe pop, soft female vocal, nylon acoustic guitar, soft Rhodes piano, brushed drums, warm bass, light bossa-tinged groove, maj7 chords, rainy and cozy, not loud, 86 BPM, G major, short 4-bar intro, catchy repetitive hook "at the window seat"
```

**Lyrics**
```
[Intro]
(rain sounds, soft guitar)

[Verse 1]
Took the window seat by accident
Where we used to sit on rainy days
Same chipped mug, same cinnamon scent
Some things never change their ways

[Pre-Chorus]
Outside the leaves are turning red
Inside it's everything you said

[Chorus]
At the window seat, at the window seat
Every raindrop sounds like we
At the window seat, I can almost see
You across from me at the window seat

[Verse 2]
Barista asks if I want the usual
I almost order two
Funny how the heart has its own schedule
Still running late for you

[Pre-Chorus]
Outside the leaves are turning red
Inside it's everything you said

[Chorus]
At the window seat, at the window seat
Every raindrop sounds like we
At the window seat, I can almost see
You across from me at the window seat

[Bridge]
I don't need you back, I just need this light
This little golden hour and I'm alright

[Final Chorus]
At the window seat, at the window seat
Every raindrop sounds like we
At the window seat, I can almost see
You across from me at the window seat

[Outro]
At the window seat... (mm)
[End]
```

### 9. 오래된 플레이리스트 | OLD PLAYLIST

**Style**
```
laid-back autumn cafe pop with light R&B groove, warm soft male vocal, soft melodic rap verse, laid-back flow, clean electric guitar, soft Rhodes, brushed drums, warm bass, head-nodding groove, 9th chords, nostalgic, not loud, 90 BPM, A major, short 4-bar intro, catchy repetitive hook "play it back"
```

**Lyrics**
```
[Intro]
(play it back, play it back)

[Verse 1]
Hit shuffle on the bus ride home
Headphones in, looking out the glass
Then that song we made our own
Comes on like it's the past

[Pre-Chorus]
Track number seven, you named it "us"
Now it's playing on a city bus

[Chorus]
Play it back, play it back
That old playlist we used to have
Play it back, play it back
Didn't know I still had that
Mm, play it back

[Rap]
Dusty little folder in the corner of my phone
Named it after nothing, now it feels like home
Every song a moment, every beat a place
Late night convenience store, the look on your face
I could hit delete, I could let it go
But some songs are better when you play them low
So I lean on the window, let the city pass by
Not crying, just smiling, let the melody fly

[Pre-Chorus]
Track number seven, you named it "us"
Now it's playing on a city bus

[Chorus]
Play it back, play it back
That old playlist we used to have
Play it back, play it back
Didn't know I still had that
Mm, play it back

[Bridge]
Some songs end, but the melody stays

[Final Chorus]
Play it back, play it back
That old playlist we used to have
Play it back, play it back
Didn't know I still had that
Mm, play it back

[Outro]
Play it back...
[End]
```

### 10. 첫 입김 | LITTLE CLOUD

**Style**
```
laid-back autumn cafe pop, soft airy female vocal, fingerpicked acoustic guitar, soft Rhodes piano, gentle glockenspiel accents, brushed drums, warm bass, slow swaying groove, maj7 chords, tender and warm, not loud, 84 BPM, E major, short 4-bar intro, catchy repetitive hook "little cloud"
```

**Lyrics**
```
[Intro]
(hoo, hoo)

[Verse 1]
Stepped outside at seven in the morning
Saw my breath for the first time this year
Little cloud that floats without a warning
Disappears like you were here

[Pre-Chorus]
Winter's knocking, autumn's leaving
And I'm breathing, just breathing

[Chorus]
Little cloud, little cloud
Every breath, I say your name out loud
Little cloud, little cloud
Floating up and fading out

[Verse 2]
You used to warm my hands in yours
Blow on them and rub them twice
Now I keep them in my pockets
And it's cold, but it's nice

[Pre-Chorus]
Winter's knocking, autumn's leaving
And I'm breathing, just breathing

[Chorus]
Little cloud, little cloud
Every breath, I say your name out loud
Little cloud, little cloud
Floating up and fading out

[Bridge]
Missing you is soft like this
Just a breath, just a little mist

[Final Chorus]
Little cloud, little cloud
Every breath, I say your name out loud
Little cloud, little cloud
Floating up and fading out

[Outro]
Little cloud... (hoo)
[End]
```

### 11. 다시, 봄처럼 | LIKE SPRING IN NOVEMBER

**Style**
```
laid-back autumn cafe pop, bright soft female vocal, acoustic guitar, soft Rhodes piano, light strings, brushed drums, warm bass, light bouncy groove, maj7 and 9th chords, hopeful and warm, not loud, 96 BPM, D major, short 4-bar intro, catchy repetitive hook "like spring in November"
```

**Lyrics**
```
[Intro]
(oh-oh-oh)

[Verse 1]
Thought my heart went quiet for the year
Put it away with my summer clothes
Then you walked in, said "is this seat clear?"
And something in me rose

[Pre-Chorus]
Everybody's getting ready for the cold
But I'm feeling something new, not old

[Chorus]
Like spring in November
Flowers where the leaves should be
Like spring in November
You're blooming inside of me
Oh-oh-oh, like spring in November

[Verse 2]
Grey clouds, but I'm humming anyway
Wearing colors that I haven't worn in years
My friends ask "what's got into you today?"
I just laugh and say "it's here"

[Pre-Chorus]
Everybody's getting ready for the cold
But I'm feeling something new, not old

[Chorus]
Like spring in November
Flowers where the leaves should be
Like spring in November
You're blooming inside of me
Oh-oh-oh, like spring in November

[Bridge]
Out of season, out of reason
Still I'm feeling it, still I'm feeling it

[Final Chorus]
Like spring in November
Flowers where the leaves should be
Like spring in November
You're blooming inside of me
Oh-oh-oh, like spring in November

[Outro]
Oh-oh-oh...
[End]
```

### 12. 두 번째 첫 데이트 | SECOND FIRST DATE

**Style**
```
laid-back autumn cafe pop with light R&B groove, warm soft male vocal, soft melodic rap verse, laid-back flow, clean electric guitar, soft Rhodes, brushed drums, warm bass, light head-nodding groove, 9th chords, sweet and hopeful, not loud, 98 BPM, F major, short 4-bar intro, catchy repetitive hook "second first date", "hello, hello" backing vocals
```

**Lyrics**
```
[Intro]
(hello, hello)

[Verse 1]
Same old corner, same street light
I'm nervous like it's the very first night
You're wearing the coat from a year ago
Some things we lost, some things we know

[Pre-Chorus]
Let's pretend we're meeting now
Hello, hi, it's nice to meet you somehow

[Chorus]
Second first date, second first date
We're a little older, it's not too late
Second first date, let's take it slow
Hello again, hello, hello

[Rap]
Look, we had our winter, had our break
Said a couple things that were a mistake
But the leaves fall down so the trees can grow
Sometimes you gotta lose it just to know
So I'm holding the door, you're rolling your eyes
Same little smile, same little surprise
No big speech, no big plan
Just a walk, just a talk, just your hand

[Pre-Chorus]
Let's pretend we're meeting now
Hello, hi, it's nice to meet you somehow

[Chorus]
Second first date, second first date
We're a little older, it's not too late
Second first date, let's take it slow
Hello again, hello, hello

[Bridge]
Different season, same two hearts
Maybe this is where it starts

[Final Chorus]
Second first date, second first date
We're a little older, it's not too late
Second first date, let's take it slow
Hello again, hello, hello

[Outro]
Hello, hello...
[End]
```

### 13. 은행잎 편지 | GOLDEN LETTER

**Style**
```
laid-back autumn cafe pop, soft female vocal, acoustic guitar, soft Rhodes piano, light celesta accents, brushed drums, warm bass, gentle bouncy groove, maj7 chords, sweet and warm, not loud, 92 BPM, C major, short 4-bar intro, catchy repetitive hook "golden letter"
```

**Lyrics**
```
[Intro]
(mm, golden)

[Verse 1]
Found a ginkgo leaf inside my door
Tucked right in the letter slot
Written on it, "remember before?"
In your handwriting, my heart just stopped

[Pre-Chorus]
Yellow like the afternoon we met
Something I could never quite forget

[Chorus]
A golden letter, golden letter
Little leaf that says it better
Than a thousand words together
You sent me a golden letter

[Verse 2]
Kept it in the pages of my book
Chapter nine, where the lovers meet
Then one night I grabbed my coat and shook
And I ran out to your street

[Pre-Chorus]
Yellow like the afternoon we met
Something I could never quite forget

[Chorus]
A golden letter, golden letter
Little leaf that says it better
Than a thousand words together
You sent me a golden letter

[Bridge]
Didn't need to write it all
Just one leaf, just one fall

[Final Chorus]
A golden letter, golden letter
Little leaf that says it better
Than a thousand words together
You sent me a golden letter

[Outro]
Golden letter... (mm)
[End]
```

### 14. 늦게 핀 꽃 | LATE BLOOM

**Style**
```
laid-back autumn cafe pop, soft warm female vocal, fingerpicked acoustic guitar, soft Rhodes piano, light cello pad, brushed drums, warm bass, gentle swaying groove, maj7 chords, tender and hopeful, not loud, 90 BPM, Bb major, short 4-bar intro, catchy repetitive hook "late bloom"
```

**Lyrics**
```
[Intro]
(ooh)

[Verse 1]
All my friends fell in love in spring
Summer songs about a summer thing
I was waiting, I was slow
Didn't know what I didn't know

[Pre-Chorus]
Now the chrysanthemums are out
And I finally know what it's about

[Chorus]
Late bloom, late bloom
Opening up in an autumn room
Late bloom, late bloom
Right on time, 'cause it's you

[Verse 2]
You don't rush me, you don't push
You just wait with me in the hush
Pouring tea while the kettle sings
Teaching me the little things

[Pre-Chorus]
Now the chrysanthemums are out
And I finally know what it's about

[Chorus]
Late bloom, late bloom
Opening up in an autumn room
Late bloom, late bloom
Right on time, 'cause it's you

[Bridge]
Some flowers need the cold to open
Some hearts need a little time

[Final Chorus]
Late bloom, late bloom
Opening up in an autumn room
Late bloom, late bloom
Right on time, 'cause it's you

[Outro]
Late bloom... (ooh)
[End]
```

### 15. 다시 너에게 | BACK TO YOU AGAIN

**Style**
```
laid-back autumn cafe pop with light R&B groove, warm soft male vocal, soft melodic rap verse, laid-back flow, acoustic guitar, soft Rhodes, brushed drums, warm bass, light head-nodding groove, 9th chords, warm and hopeful, not loud, 94 BPM, G major, short 4-bar intro, catchy repetitive hook "back to you again"
```

**Lyrics**
```
[Intro]
(back to you, back to you)

[Verse 1]
Walked a hundred roads to find my way
Every single one of them led to you
Took a train, a bus, a rainy day
Took a year to see it through

[Pre-Chorus]
I kept running from the one thing I knew
Every map I drew was a map back to you

[Chorus]
Back to you, back to you again
Like the autumn always comes back in
Back to you, back to you again
Round and round, and then, and then
I'm back to you

[Rap]
Real talk, I thought I'd do better alone
Rearranged my room, changed my ringtone
Saw the world in pictures, still I'd scroll through
Every sunset reminding me of you
Now the wind's getting cold and the days getting short
Got my heart in a suitcase, knocking at your door
Not asking for much, just a chance and a smile
Let me stay for a minute, let me stay for a while

[Pre-Chorus]
I kept running from the one thing I knew
Every map I drew was a map back to you

[Chorus]
Back to you, back to you again
Like the autumn always comes back in
Back to you, back to you again
Round and round, and then, and then
I'm back to you

[Bridge]
Every road, every turn
Every lesson that I learned
Brought me home

[Final Chorus]
Back to you, back to you again
Like the autumn always comes back in
Back to you, back to you again
Round and round, and then, and then
I'm back to you

[Outro]
Back to you...
[End]
```

### 16. 다섯 시의 햇살 | 5PM GOLD

**Style**
```
laid-back autumn cafe pop, bright soft female vocal, acoustic guitar, soft Rhodes piano, warm bass, brushed drums with light shaker, light bouncy groove, maj7 chords, golden and cozy, not loud, 98 BPM, D major, short 4-bar intro, catchy repetitive hook "five PM gold"
```

**Lyrics**
```
[Intro]
(ooh, gold)

[Verse 1]
Days got shorter, I don't mind
Sun goes early, leaves a gift behind
Every building dipped in honey light
Right before it turns to night

[Pre-Chorus]
Stop, look up, don't miss it now
The sky is putting on a show somehow

[Chorus]
Five PM gold, five PM gold
Brighter than the stories told
Just for a moment, never gets old
Five PM gold, five PM gold

[Verse 2]
Kid on a bike, an old man and his dog
Shadows stretching long and thin
Windows glowing through the evening fog
Every face is lit within

[Pre-Chorus]
Stop, look up, don't miss it now
The sky is putting on a show somehow

[Chorus]
Five PM gold, five PM gold
Brighter than the stories told
Just for a moment, never gets old
Five PM gold, five PM gold

[Bridge]
It only lasts a minute or two
Like the best things always do

[Final Chorus]
Five PM gold, five PM gold
Brighter than the stories told
Just for a moment, never gets old
Five PM gold, five PM gold

[Outro]
Five PM gold... (ooh)
[End]
```

### 17. 좋은 하루 | GOOD DAY, GOOD DAY

**Style**
```
laid-back autumn cafe pop with light R&B groove, warm soft male vocal, soft melodic rap verse, laid-back flow, acoustic guitar, soft Rhodes, brushed drums, warm bass, light bouncy head-nodding groove, 9th chords, cheerful and cozy, not loud, 100 BPM, C major, short 4-bar intro, catchy repetitive hook "good day, good day"
```

**Lyrics**
```
[Intro]
(good day, good day)

[Verse 1]
Woke up just before the alarm
Toast came out just right
Found some cash in my old coat pocket
Morning's looking bright

[Pre-Chorus]
Nothing big and nothing new
Still I've got a feeling and it's true

[Chorus]
Good day, good day, it's a good day
Nothing special, but it's okay
Good day, good day, say it with me
Good day, good day, feeling free

[Rap]
Mm, bus came on time, got a seat by the window
Old lady smiled like she knew where I'm going
Bakery's warm and the air smells sweet
Cinnamon swirl, little rhythm in my feet
No big news, no big deal
But I like the way these little things feel
Scarf on, hands warm, walking downtown
Can't stop smiling, won't bring it down

[Pre-Chorus]
Nothing big and nothing new
Still I've got a feeling and it's true

[Chorus]
Good day, good day, it's a good day
Nothing special, but it's okay
Good day, good day, say it with me
Good day, good day, feeling free

[Bridge]
Nothing happened, nothing much
That's the magic, that's the touch

[Final Chorus]
Good day, good day, it's a good day
Nothing special, but it's okay
Good day, good day, say it with me
Good day, good day, feeling free

[Outro]
Good day, good day...
[End]
```

### 18. 사소한 행복 | SMALL WONDERS

**Style**
```
laid-back autumn cafe pop, soft sweet female vocal, fingerpicked acoustic guitar, soft Rhodes piano, light glockenspiel, brushed drums, warm bass, gentle bouncy groove, maj7 chords, cozy and content, not loud, 94 BPM, F major, short 4-bar intro, catchy repetitive hook "small wonders"
```

**Lyrics**
```
[Intro]
(mm-mm)

[Verse 1]
Steam on the window from the kettle
First page of a brand new book
Socks still warm from the dryer
Worth a second look

[Pre-Chorus]
Nobody writes songs about these things
So here's the one that my heart sings

[Chorus]
Small wonders, small wonders
Everywhere I turn today
Small wonders, small wonders
Little lights along the way

[Verse 2]
Cat asleep in a square of sun
Tangerines in a paper bag
Friend who texts "you eat yet?" at one
Old song that brings you back

[Pre-Chorus]
Nobody writes songs about these things
So here's the one that my heart sings

[Chorus]
Small wonders, small wonders
Everywhere I turn today
Small wonders, small wonders
Little lights along the way

[Bridge]
You don't have to look too far
Happiness is where you are

[Final Chorus]
Small wonders, small wonders
Everywhere I turn today
Small wonders, small wonders
Little lights along the way

[Outro]
Small wonders... (mm)
[End]
```

### 19. 따뜻한 오후 | WARM AFTERNOON

**Style**
```
laid-back autumn cafe pop, warm soft male vocal, nylon acoustic guitar, soft Rhodes piano, brushed drums, warm upright-style bass, slow easy groove, maj7 and 9th chords, lazy and cozy, not loud, 92 BPM, E major, short 4-bar intro, catchy repetitive hook "warm afternoon"
```

**Lyrics**
```
[Intro]
(mm, rain on the window)

[Verse 1]
Cinnamon and apple in the air
Blanket on the sofa, feet up there
Rain is tapping softly on the pane
Nothing on my list, no need to explain

[Pre-Chorus]
Let the clock go slow today
Let the hours drift away

[Chorus]
Warm afternoon, warm afternoon
Humming an easy tune
Nowhere to be, nothing to do
Warm afternoon with you

[Verse 2]
You're reading something, I'm half asleep
Tea's gone cold but the moment keeps
Every now and then you read a line out loud
And I smile like I'm proud

[Pre-Chorus]
Let the clock go slow today
Let the hours drift away

[Chorus]
Warm afternoon, warm afternoon
Humming an easy tune
Nowhere to be, nothing to do
Warm afternoon with you

[Bridge]
If the whole world hurries by
Let it go, just you and I

[Final Chorus]
Warm afternoon, warm afternoon
Humming an easy tune
Nowhere to be, nothing to do
Warm afternoon with you

[Outro]
Warm afternoon... (mm)
[End]
```

### 20. 어깨가 가벼워 | LIGHT SHOULDERS (타이틀곡)

**Style**
```
laid-back autumn cafe pop with light R&B groove, bright soft female vocal, soft melodic rap verse, laid-back flow, acoustic guitar, soft Rhodes, brushed drums with light shaker, warm bass, light shoulder-bouncing groove, 9th chords, carefree and cozy, not loud, 100 BPM, G major, short 4-bar intro, catchy repetitive hook "light shoulders", "la-da-da" backing vocals
```

**Lyrics**
```
[Intro]
(la-da-da, la-da-da)

[Verse 1]
Put my worries in a paper bag
Left them by the bus stop sign
Wind picks up and it's not so bad
Everything's gonna be just fine

[Pre-Chorus]
One, two, let it go
Three, four, take it slow

[Chorus]
Light shoulders, light shoulders
Getting colder, but I'm feeling bolder
Light shoulders, light shoulders
Hum it, bounce it, over and over
(la-da-da, la-da-da)

[Rap]
Yeah, autumn in the city and the sky so clear
Hands in my jacket, got a song in my ear
Didn't fix my life but I fixed my mood
Warm bread, good friends, simple food
Leaves say goodbye so the tree gets light
Maybe that's the secret, maybe that's right
Let it fall, let it fall, let it drift away
Light shoulders, living for today

[Pre-Chorus]
One, two, let it go
Three, four, take it slow

[Chorus]
Light shoulders, light shoulders
Getting colder, but I'm feeling bolder
Light shoulders, light shoulders
Hum it, bounce it, over and over
(la-da-da, la-da-da)

[Bridge]
Nothing heavy, nothing tight
Just the autumn and the light

[Final Chorus]
Light shoulders, light shoulders
Getting colder, but I'm feeling bolder
Light shoulders, light shoulders
Hum it, bounce it, over and over
(la-da-da, la-da-da)

[Outro]
La-da-da... light shoulders
[End]
```
