# react-native-expandable-card
A react-native expandable and collapsible animated card

##Installation
npm install --save react-native-expandable-card

##Use
```javascript
import React from 'react';
import { View } from 'react-native';
import ExpandableCard from 'react-native-expandable-card';

const MyComponent = () => {
	return (
		<View>
			<ExpandableCard
				collapsedCardItems={[
					{label: 'title', value: 'Inception'},
					{label: 'director', value: 'Christopher Nolan'},
					{label: 'year', value: 2010}
				]}
				expandedCardItems={[
					{label: 'title', value: 'Inception'},
					{label: 'director', value: 'Christopher Nolan'},
					{label: 'genre', value: 'science-fiction'}
					{label: 'year', value: 2010}
				]}
				style={{backgroundColor: 'lightgrey', marginHorizontal: 20}}
				labelStyle={{fontFamily: 'open-sans-cond-bold'}}
				valueStyle={{fontFamily: 'open-sans-cond'}}
			/>
		</View>
	);
};

export default MyComponent;
```