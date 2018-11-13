<template>
    <Page>
        <ActionBar title="Ping" android:flat="true"/>
        <TabView android:tabBackgroundColor="#000"
                 android:tabTextColor="#fff"
                 android:selectedTabTextColor="#ffffff"
                 androidSelectedTabHighlightColor="#ffffff">
            <TabViewItem title="Main">
                <GridLayout columns="*" rows="*">
                    <Label class="message" text="Main" col="0" row="0"/>
                </GridLayout>
            </TabViewItem>
            <TabViewItem title="History">
                <GridLayout columns="*" rows="*">
                    <Label class="message" text="Tab 2 Content" col="0" row="0"/>
                </GridLayout>
            </TabViewItem>
            <TabViewItem title="Settings">
                <GridLayout columns="*" rows="*">
                    <Label class="message" text="Tab 3 Content" col="0" row="0"/>
                </GridLayout>
            </TabViewItem>
        </TabView>
    </Page>
</template>

<script>
  export default {
    data() {
      return {
        stepcounterText: 'Hello World!'
      }
    }
  }
</script>

<style scoped>
    ActionBar {
        background-color: #000;
        color: #ffffff;
    }

    .message {
        vertical-align: center;
        text-align: center;
        font-size: 20;
        color: #333333;
    }
</style>
