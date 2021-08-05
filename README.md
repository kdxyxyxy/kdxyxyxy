menu=gg.choice({'Currency hack'})

if menu==1 then

gg.setRanges(gg.REGION_ANONYMOUS)
gg.alert('Currency hack by Mythic Modz#0001, enjoy <3')
gg.alert('If it crashes the game, retry')
gg.alert('Scanning database')
gg.searchNumber('300',gg.TYPE_DWORD)
gg.getResults(10000)
gg.editAll('0',gg.TYPE_DWORD)
gg.clearResults()
end
