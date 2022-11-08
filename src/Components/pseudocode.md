Story 1 Branch vowel-functionality

Acceptance Criteria

ACTION ITEM - Can type any word that begins with a vowel in the text input (e.g. apple)
    ** vowelsArray[0] === eachWord[0] then return eachWord + "way"
   

C/W - Can hit the submit button

ACTION ITEM - Can see the words that begin with a vowel translated to Pig Latin and rendered to the page (e.g. appleway)
    **Utilize eachWord line 39 --> return eachWord + "way"     



Story 2: In order to see English words converted to Pig Latin, as the user of the application, I need to see words that have "qu" in the first syllable translated by moving all the consonant and the "u" to the end and add "ay".

Branch: qu-functionality

Acceptance Criteria

Can type any word that has a "qu" in the first syllable in the text input (e.g. squeal)
Can hit the submit button
Can see the words that have a "qu" in the first syllable translated to Pig Latin and rendered to the page (e.g. ealsquay)



Story 3: In order to see English words converted to Pig Latin, as the user of the application, I need to see words that have no vowels other than "y" translated by moving all the consonant to the end and add "ay".

Branch: y-functionality

Acceptance Criteria

Can type any word that has no vowels other than "y" in the text input (e.g. fry)
Can hit the submit button
Can see the words that have no vowels other than "y" translated to Pig Latin and rendered to the page (e.g. yfray)



Story 4: In order to see English words converted to Pig Latin, as the user of the application, I need to see words that have one or more consonants translated by moving all the consonant to the end and add "ay".

Branch: consonant-functionality

Acceptance Criteria

Can type any word that starts with one or more consonants in the text input (e.g. through)
Can hit the submit button
Can see the words that start with one or more consonants translated to Pig Latin and rendered to the page (e.g. oughthray)